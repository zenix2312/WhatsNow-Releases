# WhatsNow v0.5.0-beta.2 — Release notes

**Language:** [English](RELEASE_NOTES.md) | [Português (Brasil)](RELEASE_NOTES.pt-BR.md)

Experimental beta for Samsung Galaxy devices with compatible Now Bar notification capabilities.

## What changed

- Updated module version to `v0.5.0-beta.2` (`versionCode=57`).
- Updated version references in installer/runtime scripts.
- Maintainer/author: `zenix2312`.
- No changes to the DEX/APK binaries or core notification behavior compared with beta.1.

## Capabilities

- Firmware capability checks rather than a fixed model allowlist.
- WhatsApp notification adaptation using available system paths.
- Conversation grouping and expansion where supported.
- Safety checks and diagnostics using the module's Action screen.

## Known limitations

- Inline replies inside cards are disabled for SystemUI stability.
- Long conversation histories may be truncated.
- On-device validation is confirmed only for Galaxy A07 / Android 16 / One UI 8.5 / KernelSU. Other devices remain experimental.

## Installation

Download `WhatsNow_v0.5.0-beta.2.zip` and its matching `.sha256` from [v0.5.0-beta.2](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.2). Verify the checksum and keep a known-good backup and recovery option.

**Distribution:** original source code is private. The public module includes compiled binaries and the shell scripts necessary for installation and operation. See [terms](TERMS.md).
