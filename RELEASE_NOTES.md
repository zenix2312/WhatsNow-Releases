# WhatsNow v0.5.0-beta.1 — Release notes

**Language:** [English](RELEASE_NOTES.md) | [Português (Brasil)](RELEASE_NOTES.pt-BR.md)

Initial public beta for Samsung Galaxy devices with compatible Now Bar notification capabilities.

## Included in this beta

- Firmware capability checks instead of a fixed device allowlist.
- WhatsApp notification conversion using supported system paths.
- Conversation grouping and expansion where available.
- Runtime safety checks and diagnostics through the module's Action screen.

## Known limitations

- Inline replies inside notification cards are disabled for SystemUI stability.
- Long message histories may be truncated.
- On-device validation is confirmed only for Galaxy A07 / Android 16 / One UI 8.5 / KernelSU.

## Installation

Download `WhatsNow_v0.5.0-beta.1.zip` and its matching `.sha256` from the [GitHub release](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.1). Verify the checksum, install with a compatible root module manager and keep a working backup and recovery option available.

**Distribution:** The source code is private. The public ZIP contains compiled artifacts and the scripts needed for installation and execution, not Java source or build tools. See [terms](TERMS.md).
