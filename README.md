# DotGuard downloads

Download DotGuard for Apple Silicon Macs running macOS 15 or later.

**[Download DotGuard](https://github.com/kylon526/dotguard-downloads/releases/latest/download/DotGuard-macos-arm64.dmg)**

[Alternative ZIP](https://github.com/kylon526/dotguard-downloads/releases/latest/download/DotGuard-macos-arm64.zip) · [Release notes and checksums](https://github.com/kylon526/dotguard-downloads/releases) · [Download page](https://kylon526.github.io/dotguard-downloads/)

The archive includes the desktop app, independent menu bar monitor, CLI, gateway,
and Python runtime. It requires an existing configured DotGuard installation.
This build is ad-hoc signed and is not Apple-notarized. Automatic updating,
installation, and corruption repair are not included yet.

Your rules, protector password/key, certificate state, and network configuration
are never included in these public downloads. Source is maintained privately;
this repository contains only download information and release assets.

Closing the desktop app leaves the independent monitor and existing protection
running. See the README in the archive before replacing service components.

## First open on macOS

Open the DMG, drag **DotGuard Desktop.app** to Applications, and try opening it.
If macOS says Apple could not verify the app, click **Done**, then go to
**System Settings → Privacy & Security → Security → Open Anyway** for DotGuard.
Confirm **Open** and authenticate if asked.

This is Apple's per-app approval flow. The DMG does not remove the warning:
this build is locally signed and not Apple-notarized. Do not disable Gatekeeper
system-wide. [Apple's instructions](https://support.apple.com/en-us/102445).

Dragging the app does not replace service components or re-register an existing
monitor job. Coordinated installation and updating remain separate work.
