# Trunk NG

[![Build Status](https://github.com/ctron/trunk/actions/workflows/ci.yaml/badge.svg?branch=trunk-ng)](https://github.com/ctron/trunk/actions)
[![](https://img.shields.io/crates/v/trunk-ng.svg?color=brightgreen&style=flat-square)](https://crates.io/crates/trunk-ng)
![](https://img.shields.io/badge/license-MIT%2FApache--2.0-blue?style=flat-square)
[![Discord Chat](https://img.shields.io/discord/793890238267260958?logo=discord&style=flat-square)](https://discord.gg/JEPdBujTDr)
![](https://img.shields.io/crates/d/trunk-ng?label=downloads%20%28crates.io%29&style=flat-square)
![](https://img.shields.io/github/downloads/ctron/trunk/total?label=downloads%20%28GH%29&style=flat-square)

**Build, bundle & ship your Rust WASM application to the web.**
<br/>
*”Pack your things, we’re going on an adventure!” ~ Ferris*

Trunk is a WASM web application bundler for Rust. Trunk uses a simple, optional-config pattern for building & bundling WASM, JS snippets & other assets (images, css, scss) via a source HTML file.

> [!NOTE]
> This is a forked version of `trunk`, adding features and bug fixes which didn't get merged into trunk so far.
Replace `trunk` with `trunk-ng` for all operations.

**📦 Dev server** - Trunk ships with a built-in server for rapid development workflows, as well as support for HTTP & WebSocket proxies.

**🏗 Change detection** - Trunk watches your application for changes and triggers builds for you, including automatic browser reloading.

## Getting Started

Head on over to the [Trunk-ng website](https://ctron.github.io/trunk/), everything you need is there. A few quick links:

- [Install](https://ctron.github.io/trunk/#install)
  - Download a released binary: https://github.com/ctron/trunk/releases
  - `cargo binstall trunk-ng`
  - `cargo install --git https://github.com/ctron/trunk --branch trunk-ng trunk-ng` (most recent from git)
  - `cargo install --path . trunk-ng` (Most recent from local directory)
- [App Setup](https://ctron.github.io/trunk/#app-setup)
- [Assets](https://ctron.github.io/trunk//assets/)
- [Configuration](https://ctron.github.io/trunk//configuration/)
- [CLI Commands](https://ctron.github.io/trunk//commands/)

## Examples

Check out the example web applications we maintain in-repo under the `examples` directory.

## Contributing

Anyone and everyone is welcome to contribute! Please review the [CONTRIBUTING.md](./CONTRIBUTING.md) document for more details. The best way to get started is to find an open issue, and then start hacking on implementing it. Letting other folks know that you are working on it, and sharing progress is a great approach. Open pull requests early and often, and please use GitHub's draft pull request feature.

### License

trunk-ng is licensed under the terms of the MIT License or the Apache License 2.0, at your choosing.
