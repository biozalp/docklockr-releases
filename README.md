# DockLockr Releases

Public distribution channel for **[DockLockr](https://docklockr.app)** — a macOS menu-bar app that locks your Dock.

This repository hosts the auto-update feed and downloadable builds. The app's source code lives in a separate private repository.

- **Update feed (Sparkle appcast):** [`appcast.xml`](https://raw.githubusercontent.com/biozalp/docklockr-releases/main/appcast.xml)
- **Downloads:** each version's notarized `DockLockr.dmg` is attached as a [GitHub Release](../../releases) asset.

Builds are signed with an Apple Developer ID, notarized by Apple, and signed again with a Sparkle EdDSA key so updates are verified end-to-end.
