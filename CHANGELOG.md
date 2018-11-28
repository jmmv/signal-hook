# Upcoming (unreleased) changes

* Exposed a new `SigNo` type to represent the correct integer type for
  signal numbers.  This prevents users of this library from having to
  directly address `libc::c_int`.

# 0.1.6

* The internally used ArcSwap thing doesn't block other ArcSwaps now (has
  independent generation lock).

# 0.1.5

* Re-exported signal constants, so users no longer need libc.

# 0.1.4

* Compilation fix for android-aarch64

# 0.1.3

* Tokio support.
* Mio support.
* Dependency updates.

# 0.1.2

* Dependency updates.

# 0.1.1

* Get rid of `catch_unwind` inside the signal handler.
* Link to the nix crate.

# 0.1.0

* Initial basic implementation.
* Flag helpers.
* Pipe helpers.
* High-level iterator helper.
