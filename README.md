# Homebrew Tap for mss

Homebrew formulae for the [mss library](https://github.com/ryanthedev/mss) - macOS Scripting Addition Library for window and space management.

## Installation

```bash
brew tap ryanthedev/mss
brew install mss
```

## What is mss?

A lightweight C library for programmatic window and space management on macOS through private SkyLight APIs. Based on the [yabai project](https://github.com/koekeishiya/yabai).

### Features

- **Window Operations**: Move, resize, set opacity, change layers, focus, minimize
- **Space Management**: Create, destroy, focus, and move spaces between displays
- **Display Queries**: Get display count and list of displays
- **Cross-language Support**: Works with C, Objective-C, and Swift

## Documentation

See the [main repository](https://github.com/ryanthedev/mss) for:
- Complete API reference
- Swift integration guide
- Architecture details
- Usage examples

## System Requirements

- macOS 11.0+ (Big Sur or later)
- Xcode Command Line Tools for building

Runtime requirements for scripting addition:
- Root privileges (sudo)
- SIP partially disabled
- ARM64 Macs: boot argument `-arm64e_preview_abi`

See the [one-time setup guide](https://github.com/ryanthedev/mss#one-time-setup-requires-root--sip-disabled) for detailed setup instructions.

## Support

- **Issues**: https://github.com/ryanthedev/mss/issues
- **License**: MIT
