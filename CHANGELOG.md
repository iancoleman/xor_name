# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.2.0](https://github.com/maidsafe/xor_name/compare/v1.1.12...v1.2.0) (2021-04-19)


### Features

* Debug output with binary fmt as well ([1382403](https://github.com/maidsafe/xor_name/commit/1382403befe73de1961fcde8ec6cfa042dd36fb0))

### [1.1.12](https://github.com/maidsafe/xor_name/compare/v1.1.11...v1.1.12) (2021-03-03)

### [1.1.11](https://github.com/maidsafe/xor_name/compare/v1.1.10...v1.1.11) (2021-02-25)

### [1.1.10](https://github.com/maidsafe/xor_name/compare/v1.1.9...v1.1.10) (2021-02-09)

### [1.1.9](https://github.com/maidsafe/xor_name/compare/v1.1.8...v1.1.9) (2021-02-03)

### [1.1.8](https://github.com/maidsafe/xor_name/compare/v1.1.7...v1.1.8) (2021-02-03)

### [1.1.7](https://github.com/maidsafe/xor_name/compare/v1.1.6...v1.1.7) (2021-01-20)

### [1.1.6](https://github.com/maidsafe/xor_name/compare/v1.1.5...v1.1.6) (2021-01-14)

### [1.1.5](https://github.com/maidsafe/xor_name/compare/v1.1.4...v1.1.5) (2021-01-06)

### [1.1.4](https://github.com/maidsafe/xor_name/compare/v1.1.3...v1.1.4) (2020-11-23)

### [1.1.3](https://github.com/maidsafe/xor_name/compare/v1.1.2...v1.1.3) (2020-10-09)

### [1.1.2](https://github.com/maidsafe/xor_name/compare/v1.1.1...v1.1.2) (2020-10-09)

### [1.1.1](https://github.com/maidsafe/xor_name/compare/v1.1.0...v1.1.1) (2020-09-21)

### [1.1.0](https://github.com/maidsafe/xor_name/compare/v1.0.0...v1.1.0) (2020-08-18)
* Add in `XorName::random()` functionality
* Use OSRng

### [1.0.0](https://github.com/maidsafe/xor_name/compare/0.9.2...v1.0.0) (2020-07-02)
* Make the crate no_std
* Add impl Deref for XorName, remove slice indexing
* Minimise the API surface
* Remove generics

### [0.9.2]
* Remove test barrier from the FromStr trait impl for Prefix

### [0.9.1]
* Added borrow trait for prefix

### [0.9.0]
* Extracted from the routing crate to become standalone (again)
* License details updated to MIT or modified BSD license.
* CI set up on GitHub Actions

### [0.1.0]
* Replace CBOR usage with maidsafe_utilites::serialisation.
* Updated dependencies.

### [0.0.5]
* Migrate to maidsafe_utilities 0.2.1.
* Make debug hex output lowercase.

### [0.0.4]
* Reduce debug output to improve readability.

### [0.0.3]
* Add the `with_flipped_bit` and `count_differing_bits` methods.
* Rename `cmp_closeness` to `cmp_distance`.

### [0.0.2]
* Rename `bucket_distance` to `bucket_index`.
* Expand documentation.
* Add `XorName::cmp_closeness` ordering method.

### [0.0.1]
* Initial implementation
