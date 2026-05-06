# Sonixy

Sonixy is an Android music utility built for saving and managing music from Spotify links. It resolves Spotify metadata, finds matching audio through a YouTube-based engine, saves tracks locally, and provides an in-app playback experience.

This repository is used for public release information and downloadable APK builds. The application source code remains private.

## Highlights

- Open Spotify track, album, playlist, and artist links
- Resolve song metadata including title, artist, album, and artwork
- Download audio using a `yt-dlp` powered resolving pipeline
- Save music locally with metadata and cover art
- Fetch synced or plain lyrics when available
- Continue downloads in the background with Android foreground services
- Play downloaded music inside Sonixy
- Modern Android interface designed for mobile use

## Installation

1. Download `sonixy-xxxx-release-signed.apk` from the `releases` folder or from GitHub Releases.
2. Transfer the APK to your Android device if you downloaded it on a computer.
3. Open the APK on your device.
4. If Android asks, allow installation from your browser or file manager.
5. Complete the installation and open Sonixy.

## Verify the APK

To confirm the APK matches the published release, compare its SHA-256 checksum with the value below:

```text
B973FBF07AD4EC28B54B396F2EDD44D81E676FF4C3FE7EABFD0164C99C46CA7E
```

On Windows PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\releases\sonixy-v1.0-release-signed.apk
```

## Android Support

- Minimum Android version: Android 7.0, API 24
- Target Android version: Android 14, API 34
- Supported CPU architecture: `arm64-v8a`

## Repository Status

This is a closed-source release repository. Source code, internal build files, signing keys, and private assets are not included.

## License

See [`LICENSE`](LICENSE).
