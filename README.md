<div align="center">

# 🎵 Sonixy

**The High-Speed Spotify Music Downloader & Ambient Audio Player**
*Available on Android & Windows Desktop*

[![Latest Release](https://img.shields.io/github/v/release/nourddinak/sonixy?label=Latest%20Release&style=for-the-badge&color=8b5cf6)](https://github.com/nourddinak/sonixy/releases/latest)
[![Latest Downloads](https://img.shields.io/github/downloads/nourddinak/sonixy/latest/total?label=Latest%20Downloads&style=for-the-badge&color=06b6d4)](https://github.com/nourddinak/sonixy/releases/latest)
[![GitHub Stars](https://img.shields.io/github/stars/nourddinak/sonixy?style=for-the-badge&color=eab308)](https://github.com/nourddinak/sonixy/stargazers)
[![License](https://img.shields.io/github/license/nourddinak/sonixy?style=for-the-badge&color=10b981)](LICENSE)
[![Android](https://img.shields.io/badge/Android-7.0%2B%20(API%2024%2B)-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/nourddinak/sonixy/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/nourddinak/sonixy/releases/latest)

<br/>

[**🌐 Visit Official Website**](https://nourddinak.github.io/sonixy/) • [**📥 Download Latest Release**](https://github.com/nourddinak/sonixy/releases/latest) • [**📋 Changelog**](RELEASES.md) • [**🐞 Report Issue**](https://github.com/nourddinak/sonixy/issues)

</div>

---

## ⚡ Direct 1-Click Downloads

| Platform | File | Version | Size | Direct Download |
| :--- | :--- | :--- | :--- | :--- |
| **Android** | `sonixy-v1.2.6-release-signed.apk` | **v1.2.6** | ~40.0 MB | [**📥 Download APK**](https://github.com/nourddinak/sonixy/releases/download/v1.2.6/sonixy-v1.2.6-release-signed.apk) |
| **Windows Desktop** | `Sonixy-Desktop-Setup-1.2.6.exe` | **v1.2.6** | ~106.4 MB | [**📥 Download .exe**](https://github.com/nourddinak/sonixy/releases/download/v1.2.6/Sonixy-Desktop-Setup-1.2.6.exe) |

---

## 🌟 Key Features

### 🚀 High-Speed Downloader Engine
- **Spotify Link Support**: Paste any Spotify single track, full album, curated playlist, or artist discography URL.
- **Smart Metadata Extraction**: Automatically embeds title, artists, album, year, disc number, and ultra-high-resolution album artwork.
- **Background Downloads**: Powered by native Android Foreground Services for continuous downloads even with the screen off.

### 🎤 Synced Karaoke Lyrics
- **Real-Time LRC Support**: Displays synchronized, syllable-accurate lyrics in real-time.
- **Auto-Lyrics Search**: Built-in scraper searches LRCLib and saves `.lrc` sidecars for missing tracks with one tap.

### 📱 Fluid 60fps Mobile UI (Android)
- **Zero-Lag Architecture**: Decoupled Jetpack Compose hierarchy guarantees smooth scrolling with zero dropped frames.
- **Zero-Stutter Player Overlay**: Fluid vertical swipe-to-dismiss powered by hardware `Modifier.graphicsLayer` transforms and spring motion.
- **Reels Tab**: Immersive full-screen short music video feeds.
- **Library Organization**: Organize by folders, custom playlists, artists, and favorites with batch move, delete, and search.

### 🖥️ Ambient Desktop Companion (Windows)
- **Dynamic Ambient Glow**: Player background adapts dynamically to the dominant colors of the active album art.
- **Local Network Casting (mDNS)**: Discover and control desktop playback directly from your Android phone over Wi-Fi.
- **Built-in Auto-Updater**: Automatically updates in the background whenever new releases are published.

### 🚗 Drive Mode Suite
- **In-Car Touch Interface**: AMOLED high-contrast UI with oversized 80dp touch targets and swipe-to-skip gestures for safe driving.

---

## 📲 Installation Guide

### Android
1. Download [**`sonixy-v1.2.6-release-signed.apk`**](https://github.com/nourddinak/sonixy/releases/download/v1.2.6/sonixy-v1.2.6-release-signed.apk).
2. Tap the downloaded `.apk` in your notifications or file manager.
3. Allow *"Install unknown apps"* if prompted by Android.
4. Launch Sonixy and enjoy!

### Windows
1. Download [**`Sonixy-Desktop-Setup-1.2.6.exe`**](https://github.com/nourddinak/sonixy/releases/download/v1.2.6/Sonixy-Desktop-Setup-1.2.6.exe).
2. Run the installer. It will install the application and create a Desktop shortcut.
3. Future updates are applied automatically in the background.

---

## 🔐 Checksum & Verification

Verify the integrity of downloaded files using PowerShell or Bash:

### Android APK (`v1.2.6`)
```powershell
Get-FileHash -Algorithm SHA256 .\sonixy-v1.2.6-release-signed.apk
```
```text
SHA-256: 0856C348CE725A8E022C62B18638DFA0974F0B3429F57AEFC2CCE1A067723200
```

### Windows Installer (`v1.2.6`)
```powershell
Get-FileHash -Algorithm SHA256 .\Sonixy-Desktop-Setup-1.2.6.exe
```
```text
SHA-256: 5739372F94AFCE120A00BC7C1BA233A402DFF077CD74E6FDC98825CBD8E94DC6
```

---

## 🛠️ Technology Stack

- **Android App**: Kotlin, Jetpack Compose, Media3 / ExoPlayer, Chaquopy (Embedded Python runtime), Coroutines & Flow, Ktor Netty, Material 3.
- **Desktop App**: Electron, Vite, TypeScript, Tailwind CSS, WebSockets, Bonjour/mDNS.
- **Audio & Metadata Engine**: Python 3.8+ runtime, `yt-dlp`, SpotDL resolver, Mutagen ID3/FLAC tagger.

---

## 📄 License & Credits

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

*Created with ❤️ by [nourddinak](https://github.com/nourddinak).*
