## 0.2.1  2022-07-01

* It is now possible to set the `LIBPG_QUERY_PATH` env var when running
  `cargo` to use the system's libpg_query header and library, rather than
  using the vendored source.

## 0.2.0  2022-04-10

* Bumped the version of the libpg_query library that this crate wraps to the
  13-2.1.0 tag. Based on PR #3 from Christopher Dignam.

## 0.1.3  2021-04-25

* Update the bindgen dep to the latest version. This eliminates a number of
  outdated crates from the dep tree.

* Switch the license to BSD-3-Clause. Requested by Lukas Fittl. This addresses
  GitHub #1.
