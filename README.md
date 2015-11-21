# Fork of std::collections::HashMap

A fork of Rust's `std::collections::HashMap` type that has some minor
changes. This fork only exists as a band-aid until the changes are
implemented in Rust's stdlib.

## Changes

* Added `HashMap::take` which is the same as `HashMap::remove` but also
  returns the key.
* Added `HashMap::entry2` to take a `Cow` key.
* Added `::key` to the various `Entry` types

Forked from `d1c7a93eff5bd27632130cc5bcdaac54c32bca08`
