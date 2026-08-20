# Changelog

All notable changes to this project are documented in this file. Releases use
[Semantic Versioning](https://semver.org/) and are prepared from Conventional
Commit messages by Release Please.

## [0.3.0](https://github.com/cnjax/doubao-asr-rust/compare/v0.2.0...v0.3.0) (2026-08-20)


### Features

* add Docker deployment and automated releases ([5e430e2](https://github.com/cnjax/doubao-asr-rust/commit/5e430e292c5636ee19d6d27b44de77207493e438))
* **release:** publish macOS x86_64 and aarch64 binaries ([34c802b](https://github.com/cnjax/doubao-asr-rust/commit/34c802b7c622386e8cb83dddb78a32c2dfccc8dc))


### Bug Fixes

* **ci:** allow manual release runs without an existing tag ([843770d](https://github.com/cnjax/doubao-asr-rust/commit/843770dab4a573fbe73d44db56375e6e9a81d440))
* make container smoke checks pipefail safe ([996382c](https://github.com/cnjax/doubao-asr-rust/commit/996382c87aaed98360441d89dc3f0a2812a9d196))


### Performance Improvements

* **ci:** build linux aarch64 on a native arm64 runner ([62d4bd0](https://github.com/cnjax/doubao-asr-rust/commit/62d4bd043cc70dda26a70bf1fdd49948804436e0))

## [0.2.0](https://github.com/6Kmfi6HP/doubao-asr-rust/compare/v0.1.0...v0.2.0) (2026-08-08)


### Features

* add Docker deployment and automated releases ([5e430e2](https://github.com/6Kmfi6HP/doubao-asr-rust/commit/5e430e292c5636ee19d6d27b44de77207493e438))


### Bug Fixes

* make container smoke checks pipefail safe ([996382c](https://github.com/6Kmfi6HP/doubao-asr-rust/commit/996382c87aaed98360441d89dc3f0a2812a9d196))

## 0.1.0

- Initial asynchronous Rust SDK and command-line client.
- OpenAI-compatible Chat Completions server.
- Persistent credentials with proactive refresh and rejection recovery.
