# Sonixy

Sonixy is an Android music app for downloading, saving, organizing, and playing music from Spotify links.

This folder contains the public release files for Sonixy, including signed APK builds, release notes, and checksums.

## Latest Release

[![Latest Release](https://img.shields.io/github/v/release/nourddinak/sonixy?label=Latest%20Release&style=for-the-badge)](https://github.com/nourddinak/sonixy/releases/latest)
[![Latest Downloads](https://img.shields.io/github/downloads/nourddinak/sonixy/latest/total?label=Latest%20Downloads&style=for-the-badge)](https://github.com/nourddinak/sonixy/releases/latest)
[![All Releases](https://img.shields.io/badge/View-All%20Releases-181717?style=for-the-badge&logo=github)](https://github.com/nourddinak/sonixy/releases)

Download the newest APK from:

```text
https://github.com/nourddinak/sonixy/releases/latest
```

## Features

- Spotify track, album, playlist, and artist link support.
- Local audio downloads powered by a `yt-dlp` based resolver.
- Metadata cleanup for title, artist, album, and cover art.
- Synced and plain lyrics support when available.
- Background downloads using Android foreground services.
- Built-in local music player with notification and lock-screen controls.
- Library folders, favorites, folder search, selection, move, and delete tools.
- No Lyrics folder and folder-level lyrics search for missing lyric sidecars.
- In-app update checks from GitHub Releases.
- Update download progress and installer launch from Settings.

## Install

1. Open the latest GitHub release.
2. Download the signed APK asset.
3. Open the APK on your Android device.
4. Allow installs from your browser or file manager if Android asks.
5. Finish installation and open Sonixy.

Android only allows updating when the new APK has a higher `versionCode` and uses the same signing key.

## In-App Updates

Sonixy can check GitHub Releases for a newer APK.

- If a new version is available, Sonixy can show a launch popup.
- `Download` opens Settings and starts the update download there.
- `Later` closes the popup and can show it again next launch.
- `Don't show again` ignores only that version until a newer release is published.

## Verify APK

Use PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\releases\sonixy-v1.2-release-signed.apk
```

Expected SHA-256:

```text
0100C3F212CFEB18EC1856C51A1ACEA6095129FA4319DD6101F36D4DF790B54B
```

## Android Support

- Minimum Android version: Android 7.0, API 24
- Target Android version: Android 14, API 34
- Supported ABIs: `arm64-v8a`, `x86_64`

`arm64-v8a` supports modern Android phones. `x86_64` supports modern Android emulators.

## Release History

See [`RELEASES.md`](RELEASES.md) for all versions, release notes, APK filenames, and checksums.

## License

See [`LICENSE`](LICENSE).

---
*Created with ❤️ by the nourddinak.*
