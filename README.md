# Base16 Builder Rust

[![crats.io](https://img.shields.io/crates/v/base16-builder.svg)](https://crates.io/crates/base16-builder)
[![Build Status](https://gitlab.com/ilpianista/base16-builder-rust/badges/master/pipeline.svg)](https://gitlab.com/ilpianista/base16-builder-rust/pipelines)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Filpianista%2Fbase16-builder-rust.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Filpianista%2Fbase16-builder-rust?ref=badge_shield)

A Rust implementation of a base16 builder that follows the conventions described at https://github.com/chriskempson/base16.

Version 0.9.1.

## Installation

### From sources

    git clone https://github.com/ilpianista/base16-builder-rust
    cd base16-builder-rust
    cargo build

## Usage

    target/debug/base16-builder update
Updates all scheme and template repositories as defined in `schemes.yaml` and `templates.yaml`.

    target/debug/base16-builder
Build all templates using all schemes

## Donate

Donations via [Liberapay](https://liberapay.com/ilpianista) or Bitcoin (1Ph3hFEoQaD4PK6MhL3kBNNh9FZFBfisEH) are always welcomed, _thank you_!

## License

MIT


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Filpianista%2Fbase16-builder-rust.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Filpianista%2Fbase16-builder-rust?ref=badge_large)