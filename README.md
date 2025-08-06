# typstudio

![](.github/assets/screenshot.png)

## Features

- [x] Syntax highlighting
- [x] Compiler error markers
- [x] Real time preview
    - [ ] Navigate to source
    - [x] More performance optimization
- [x] Build/export
- [ ] Complete file explorer system
- [x] Auto complete
- [x] Image pasting
- [ ] Linting and formatting
- [ ] Bibliography assistant
- [ ] Formatting assistant
- [ ] Project creation assistant / templates

...and more to come!

## Installing & Running

Typstudio does not have a stable release yet.

### Development Builds

Development builds are provided in [releases](https://github.com/green960317/typstudio/releases).
The builds support Linux (amd64), macOS (amd64, aarch64), and Windows (amd64).

### Packages

**Unstable:**

### Note about running on macOS

When running Typstudio for the first time on macOS, you may see a warning saying that the "Developer can not be
verified". This is only a one-time warning for new files downloaded from the internet that aren't notarized.

To be able to work around it, perform the following steps:

- Right-click on the application, and then click "Open"
- Then, you'll see *yet another* warning from Gatekeeper, just click "Open" again to launch Typstudio

## Development

Do note that development (debug) builds are slower than release builds. Pull requests are welcome!

### Prerequisites

- [pnpm](https://pnpm.io/) and [Node.js](https://nodejs.org/en)
- [Rust toolchain](https://www.rust-lang.org/tools/install)
- [Tauri prerequisites](https://tauri.app/v1/guides/getting-started/prerequisites)

### Getting Started

```bash
pnpm install
pnpm tauri dev # or cargo-tauri dev
```

### Building (Release)

```bash
pnpm tauri build # or cargo-tauri build
```
