# polynomial-rs

[![maintenance status: passively-maintained](https://img.shields.io/badge/maintenance-passively--maintained-yellowgreen.svg)](https://doc.rust-lang.org/cargo/reference/manifest.html#the-badges-section)
[![license](https://img.shields.io/crates/l/polynomial.svg)](LICENSE)
[![crates.io](https://img.shields.io/crates/v/polynomial.svg)](https://crates.io/crates/polynomial)
[![docs.rs](https://img.shields.io/docsrs/polynomial/latest)](https://docs.rs/polynomial/latest/)
[![rust 1.70.0+ badge](https://img.shields.io/badge/rust-1.70.0+-93450a.svg)](https://doc.rust-lang.org/cargo/reference/manifest.html#the-rust-version-field)
[![Rust CI](https://github.com/gifnksm/polynomial-rs/actions/workflows/rust-ci.yml/badge.svg)](https://github.com/gifnksm/polynomial-rs/actions/workflows/rust-ci.yml)
[![codecov](https://codecov.io/gh/gifnksm/polynomial-rs/branch/master/graph/badge.svg?token=0RxeiNjQNM)](https://codecov.io/gh/gifnksm/polynomial-rs)

A library for manipulating polynomials.

[Documentation](https://docs.rs/polynomial/latest/polynomial/)

## How to use?

Add this to your `Cargo.toml`:

```toml
[dependencies]
polynomial = "0.2.5"
```

## Minimum supported Rust version (MSRV)

The minimum supported Rust version is **Rust 1.70.0**.
At least the last 3 versions of stable Rust are supported at any given time.

While a crate is pre-release status (0.x.x) it may have its MSRV bumped in a patch release.
Once a crate has reached 1.x, any MSRV bump will be accompanied with a new minor version.
