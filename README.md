# Enthalpy releases

This repository contains public limited-preview installation packages, checksums, release notes, and the Application update manifest for Enthalpy. It does not contain Enthalpy source code.

## Install 0.3.0

Version 0.3.0 is the first update-capable bootstrap version. You must install this version manually.

### macOS ARM64

1. Open the [v0.3.0 release](https://github.com/morochena/enthalpy-releases/releases/tag/v0.3.0).
2. Download `Enthalpy-0.3.0-macos-arm64.dmg` and its `.sha256` file.
3. Confirm that the downloaded DMG has the checksum in the `.sha256` file.
4. Open the DMG and move Enthalpy to Applications.

The macOS application is signed with an Apple Developer ID and is notarized by Apple. This package supports Apple silicon only.

### Windows x64

1. Open the [v0.3.0 release](https://github.com/morochena/enthalpy-releases/releases/tag/v0.3.0).
2. Download `Enthalpy-0.3.0-windows-x64-setup.exe` and its `.sha256` file.
3. Confirm that the downloaded installer has the checksum in the `.sha256` file.
4. Run the installer. It installs Enthalpy for the current user.

The Windows package does not have an Authenticode signature during this limited preview. Windows can show a security warning. Do not turn off Windows security. Install the package only if you accept this preview limit.

## Application updates

The installed update path is still in acceptance testing. Do not rely on automatic updates yet. After acceptance is complete, Enthalpy will download and verify a new preview version in the background. It will restart only after you select Restart.

The stable preview manifest is at [updates/preview.json](https://morochena.github.io/enthalpy-releases/updates/preview.json).

## Preview limits

These packages are for a limited preview with family and friends. They are not a supported public distribution. The supported targets are macOS on Apple silicon and Windows x64.
