
# build-qrc &emsp; [![Build Status](https://travis-ci.org/dathinab/build-qrc.svg?branch=master)](https://travis-ci.org/dathinab/build-qrc)

**A rust build dependency to build and include resources based on the Qt Resource system**

---

This crate can be used as a build dependencies. It provites a utility for
`build.rs` files to build and include resources based on the Qt Resource
system. With this any Qt bindings can use the "in the normal qt/qml way"
(E.g. by loading a resource with a `qrc:/`-scheme URL).

This crate for now provides following utilites:

(strice through means not yet implemented)

- ~~including resources based on a `.qrc` file~~
- ~~handling multiple sources (`.qrc` files)~~
- ~~automaticaly generate a `.qrc` file on build~~
  - ~~based on a files in a folder~~
  - ~~with filters~~
- ~~configure through `Cargo.toml` metatables~~
- ~~generate/use `.rcc` files~~

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any
additional terms or conditions.
