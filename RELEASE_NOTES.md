# WhatsNow v0.5.0-beta.1

Initial public beta binary release for Samsung Galaxy devices with compatible Now Bar capabilities.

- Firmware capability checks rather than a fixed Samsung device allowlist.
- WhatsApp notification conversion using supported native paths.
- Conversation grouping and expansion where supported.
- Runtime safety checks and diagnostic Action view.

**Known limitations:** inline reply inside cards disabled for stability; long histories may be truncated; only Galaxy A07 / Android 16 / One UI 8.5 / KernelSU has confirmed device validation.

Download `WhatsNow_v0.5.0-beta.1.zip`, verify its SHA-256 using the companion `.sha256`, then install from your root module manager. Keep a previous working build and recovery option available.

**Source code is private.** This release includes compiled artifacts and the installer/runtime shell scripts required to operate the module, not Java source or build tools.
