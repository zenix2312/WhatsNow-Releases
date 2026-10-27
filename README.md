# WhatsNow

**Language:** [English](README.md) | [Português (Brasil)](README.pt-BR.md)

WhatsApp notifications in the Samsung Now Bar on technically compatible Galaxy devices.

**Latest beta:** [v0.5.0-beta.2](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.2) · Maintainer: **zenix2312**

[Download beta](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.2) · [Release notes](RELEASE_NOTES.md) · [Distribution terms](TERMS.md)

## About

WhatsNow is a root module that adapts supported WhatsApp notifications to the Samsung Now Bar, when the device firmware provides the required capabilities. The presence of a Now Bar does **not** guarantee that the underlying integration is supported.

This public repository provides compiled releases and documentation. The source code is maintained separately in a private repository; WhatsNow is **not open source**.

## Compatibility

**Tested:** Samsung Galaxy A07, Android 16, One UI 8.5, KernelSU.

**Other Samsung Galaxy devices:** experimental. Compatibility depends on the specific firmware's Now Bar notification capabilities and must be tested on each device. Support for root module managers other than KernelSU has not been confirmed.

## Installation

1. Download the module ZIP and matching `.sha256` file from the [release page](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.2).
2. Verify the checksum; keep a known-good backup and a recovery method.
3. Install through a compatible root module manager.
4. Check the module's **Action** screen for diagnostics, then test actual WhatsApp notifications.
5. If SystemUI becomes unstable, disable the module and follow your device's recovery procedure.

## Current limitations

- Replying inline inside the Now Bar card is disabled for stability.
- Long conversation histories may be truncated.
- Broad device and firmware compatibility has not yet been verified.

## Bug reports

Include the Samsung model, Android and One UI versions, module manager/version, steps to reproduce, and expected versus actual behavior. Remove private messages, phone numbers, device IDs and sensitive logs before posting.

## Distribution

The original source is private. The downloadable module contains compiled binaries and the runtime/installer shell scripts needed to install it. Downloading the ZIP does not authorize redistributing modified or rebranded releases. See [distribution terms](TERMS.md).

WhatsNow is an independent project and is not affiliated with Samsung or Meta. Names and trademarks belong to their owners.
