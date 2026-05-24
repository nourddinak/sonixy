# Sonixy

Sonixy is a music ecosystem featuring an Android app and a companion Desktop App for downloading, saving, organizing, and playing music from Spotify links.

This folder contains the public release files for Sonixy, including signed APK builds, Desktop Setup executables, release notes, and checksums.

## Latest Release

[![Latest Release](https://img.shields.io/github/v/release/nourddinak/sonixy?label=Latest%20Release&style=for-the-badge)](https://github.com/nourddinak/sonixy/releases/latest)
[![Latest Downloads](https://img.shields.io/github/downloads/nourddinak/sonixy/latest/total?label=Latest%20Downloads&style=for-the-badge)](https://github.com/nourddinak/sonixy/releases/latest)
[![All Releases](https://img.shields.io/badge/View-All%20Releases-181717?style=for-the-badge&logo=github)](https://github.com/nourddinak/sonixy/releases)

Download the newest APK from:

```text
https://github.com/nourddinak/sonixy/releases/latest
```

Current packaged releases in this folder:

```text
releases/sonixy-v1.2.3-release-signed.apk
releases/desktop/Sonixy Desktop Setup 1.2.3.exe
releases/desktop/latest.yml
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
- First-install and update onboarding pages.
- Redesigned now-playing overlay with animated cover art, wavy progress, bottom controls, and next-song previews.
- Favorite Artists picker and pinned favorite artist row.
- Theme-aware sleep timer and volume overlays.
- Responsive light and dark UI polish across Downloader, Library, Artists, folders, and player screens.
- Zero-lag decoupled home feed architecture with 60fps scrolling.
- Global region and category filtering chips for trending discovery.
- Premium glassmorphic redesign of track cards and onboarding screens.

### Desktop App Features
- Immersive ambient player with synced lyrics and dynamic background glow.
- Local network discovery (mDNS/Bonjour) to automatically find and cast music from your phone.
- Cross-device playback control and synced states between Phone and PC.
- Built-in background Auto-Updater from GitHub Releases.

## Install (Mobile)

1. Open the latest GitHub release.
2. Download the signed APK asset.
3. Open the APK on your Android device.
4. Allow installs from your browser or file manager if Android asks.
5. Finish installation and open Sonixy.

Android only allows updating when the new APK has a higher `versionCode` and uses the same signing key.

## Install (Desktop)

1. Open the latest GitHub release.
2. Download `Sonixy Desktop Setup 1.2.3.exe`.
3. Run the installer. It will install the app and automatically create a desktop shortcut.
4. The desktop app will automatically update itself in the background when newer releases are published to GitHub!

## In-App Updates

Sonixy can check GitHub Releases for a newer APK.

- If a new version is available, Sonixy can show a launch popup.
- `Download` opens Settings and starts the update download there.
- `Later` closes the popup and can show it again next launch.
- `Don't show again` ignores only that version until a newer release is published.

## Verify APK

Use PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\releases\sonixy-v1.2.3-release-signed.apk
```

Expected SHA-256:

```text
8DCE6594B32081D5E64916706227862676935F3B6908F493EF8EE8551C411C9B
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
