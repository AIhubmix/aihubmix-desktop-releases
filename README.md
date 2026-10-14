# AIHubMix Desktop Releases

Download AIHubMix Desktop for macOS and Windows from the [latest release](https://github.com/AIhubmix/aihubmix-desktop-releases/releases/latest).

| Platform | Installer |
| --- | --- |
| Mac with Apple Silicon | `AIHubMix_<version>_mac-arm64.dmg` |
| Mac with an Intel processor | `AIHubMix_<version>_mac-x64.dmg` |
| Windows x64 | `AIHubMix_<version>_win-x64-setup.exe` |
| Windows ARM64 | `AIHubMix_<version>_win-arm64-setup.exe` |

macOS requires version 12 or later. Open the DMG, drag AIHubMix into Applications, and launch it. macOS packages are signed with Developer ID and notarized by Apple.

Windows installation may require an internet connection to install WebView2. Windows installers are not yet Authenticode-signed; Windows may show an unknown publisher or SmartScreen prompt.

This repository contains installers and update manifests. In-app updates use `latest.json` and verify update packages against the public key built into the app. You can also verify downloads using the release's `SHA256SUMS` file.
