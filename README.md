# Desktop Postflop

---

A free, open-source GTO solver for Texas hold'em poker

> **Fork**: This is a fork of [desktop-postflop](https://github.com/b-inary/desktop-postflop) by [b-inary](https://github.com/b-inary).

**Related repositories**

- Solver engine: https://github.com/thomas-fazzari/postflop-solver

## About

**Desktop Postflop** is a native desktop application for GTO poker analysis using [Tauri 2].

[Tauri 2]: https://v2.tauri.app/

## Supported environments

- OS
  - Windows: 10/11
  - macOS: 11.7 and later
  - Linux: glibc 2.31 and later (e.g., Ubuntu 20.04 and later)
- CPU
  - x86-64: must support AVX2 instructions
    - Intel: Haswell (2013) and later
    - AMD: Zen (1st gen; 2017) and later
  - Apple silicon: M1 and later

## Build

[Rust] and [Node.js] need to be installed to build.
On Linux, you will also need to install some dependencies; please see the [Tauri documentation] for details.

Then clone this repository and run the following commands:

```sh
$ npm install
$ npm run tauri build
```

If the build was successful, you should be able to find the application in the `src-tauri/target/release/bundle/` directory.

[Rust]: https://www.rust-lang.org/learn/get-started
[Node.js]: https://nodejs.org/en/
[Tauri documentation]: https://tauri.app/v1/guides/getting-started/prerequisites/#setting-up-linux

## License

Copyright (C) 2022 Wataru Inariba (original work)
Copyright (C) 2026 Thomas Fazzari (fork)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
