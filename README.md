# WhatsNow

A root module for compatible Samsung Galaxy Now Bar notifications from WhatsApp.

**Latest beta:** [v0.5.0-beta.1](https://github.com/zenix2312/WhatsNow-Releases/releases/tag/v0.5.0-beta.1) · Maintainer: **zenix2312**

[Português (Brasil)](README.pt-BR.md) | [Releases](https://github.com/zenix2312/WhatsNow-Releases/releases)

## About

WhatsNow adapts supported WhatsApp notifications to Samsung's Now Bar when the installed firmware exposes the required capabilities. Availability of Now Bar alone does not guarantee compatibility.

This is a **binary-distribution repository**. The source code and build tools are maintained in a private repository; this repository does not provide an open-source license.

## Compatibility

Confirmed test environment: Samsung Galaxy A07, Android 16, One UI 8.5 and KernelSU. Other models and One UI versions require testing. Module-manager support other than KernelSU has not been verified on real devices.

## Install

1. Download the ZIP and corresponding SHA-256 file from the latest beta release.
2. Verify the checksum, and keep a known-good backup and recovery path.
3. Install using your compatible root module manager.
4. Check the module's Action view for compatibility status, then test with actual WhatsApp notifications.
5. If SystemUI misbehaves, disable the module and follow your device recovery procedure.

## Known limitations

- Inline replies from inside the card remain disabled in this beta for stability.
- Long conversation history may be truncated on some firmwares.
- Compatibility and stability across devices remain unverified outside the test configuration.

## Reporting issues

Specify Samsung model, Android and One UI versions, module manager and version, expected/observed behavior, and steps to reproduce. **Redact** messages, phone numbers, device identifiers and private logs.

## Terms

The original WhatsNow code is privately maintained by zenix2312. The released ZIP is provided for personal testing. No permission is granted to redistribute modified or rebranded builds without authorization. See [distribution terms](TERMS.md).

WhatsNow is an independent project, not affiliated with Samsung or Meta. Names and trademarks belong to their respective owners.
