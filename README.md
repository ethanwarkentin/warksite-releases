# Warksite releases

Installers and update manifests for Warksite. **This repo holds releases only; the source code is private.**

- **Desktop (Windows):** download `Warksite_<version>_x64-setup.exe` from the latest `desktop-v*` release. The installed app updates itself after that.
- **Android:** download `warksite-<version>.apk` from the latest `mobile-v*` release. The app offers updates after that.

`updates/desktop.json` and `updates/mobile.json` are the manifests the apps check. CI in the private repo publishes them; don't edit them by hand.
