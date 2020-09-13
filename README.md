# Fork
This fork goal is to remove dependencies as much as possible (33 total dependency instead of 130)

Diffrence from the original:
- serde replaced with nanoserde
- reqwest replaced with ureq
- no async client

Uptodate with commit 34e5f07a442d3a83e1d93fbf3a5f79e4a60c12c9

# crates_io_api

A Rust client for the [crates.io](https://crates.io) API.

This crate aims to provide an easy to use and complete client for retrieving
detailed information about Rust's crate ecosystem.

The crate uses the [reqwest](https://github.com/seanmonstar/reqwest) HTTP client
and provides both a async and synchronous interface.

Please consult the official [Crawler Policy](https://crates.io/policies#crawlers) before using this library. 
A rate limiter is included.

## How to use

For usage information and examples, check out the
[Documentation](https://docs.rs/crates_io_api).
