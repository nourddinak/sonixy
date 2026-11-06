<div align="center">

<img src=".github/assets/logo.png" alt="Sonixy logo" width="128" height="128" />

# Sonixy

### Free music downloader & offline player for Android, with Sonixy Connect for Windows and Mac

Paste a link from **Spotify, YouTube, SoundCloud, Deezer, Apple Music, TikTok** and more, and get properly tagged tracks with album art and synced lyrics, ready to play offline.

[![Latest Release](https://img.shields.io/github/v/release/nourddinak/sonixy?label=Latest&style=for-the-badge&color=8b5cf6)](https://github.com/nourddinak/sonixy/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/nourddinak/sonixy/total?label=Downloads&style=for-the-badge&color=06b6d4)](https://github.com/nourddinak/sonixy/releases)
[![Stars](https://img.shields.io/github/stars/nourddinak/sonixy?style=for-the-badge&color=eab308)](https://github.com/nourddinak/sonixy/stargazers)
[![License: Freeware](https://img.shields.io/badge/License-Freeware-10b981?style=for-the-badge)](LICENSE)
<br/>
[![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/nourddinak/sonixy/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/nourddinak/sonixy/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-12%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/nourddinak/sonixy/releases/latest)

**[🌐 Website](https://nourddinak.github.io/sonixy/)** ·
**[📥 Download](https://github.com/nourddinak/sonixy/releases/latest)** ·
**[📋 Changelog](RELEASES.md)** ·
**[🐞 Report a bug](https://github.com/nourddinak/sonixy/issues/new)**

<br/>

<img src=".github/assets/screenshots/downloader.jpg" alt="Downloader" width="19%" />
<img src=".github/assets/screenshots/library.jpg" alt="Library" width="19%" />
<img src=".github/assets/screenshots/player.jpg" alt="Player" width="19%" />
<img src=".github/assets/screenshots/drive-mode.jpg" alt="Drive Mode" width="19%" />
<img src=".github/assets/screenshots/desktop-sync.jpg" alt="Desktop sync" width="19%" />

</div>

---

## 📥 Download

| Platform | Version | Size | Download |
| :--- | :---: | :---: | :--- |
| **Android** (7.0+) | **v1.4.1** | ~37.3 MB | [**Sonixy-v1.4.1-code13-release.apk**](https://github.com/nourddinak/sonixy/releases/download/v1.4.1/Sonixy-v1.4.1-code13-release.apk) |
| **Windows** (10 / 11): Sonixy Connect | **v2.0.1** | ~100.7 MB | [**Sonixy-Connect-Setup-2.0.1.exe**](https://github.com/nourddinak/sonixy/releases/download/v1.4.1/Sonixy-Connect-Setup-2.0.1.exe) |
| **macOS** (12+, Intel & Apple silicon): Sonixy Connect | **v2.0.0** | ~218.3 MB | [**Sonixy-Connect-2.0.0-mac.dmg**](https://github.com/nourddinak/sonixy/releases/download/v1.4.0/Sonixy-Connect-2.0.0-mac.dmg) |

> Only download Sonixy from this repository's [Releases page](https://github.com/nourddinak/sonixy/releases) or the [official website](https://nourddinak.github.io/sonixy/). Check the SHA-256 hashes [below](#-verify-your-download).

---

## ✨ Why Sonixy

- 🔗 **One link, any source.** Single tracks, albums, playlists and artist pages.
- 🏷️ **Clean files.** Title, artist, album, year, track number and high-res cover art written into every file.
- 🎤 **Synced lyrics.** Karaoke-style timed lyrics, fetched automatically from LRCLib and saved as `.lrc`.
- 📴 **Built for offline.** Your music lives on your device, organized by folders, artists, albums and playlists.
- 🆓 **Free, no ads, no account.**

## 🌍 Supported sources

| Music | Video & social | Anything else |
| :--- | :--- | :--- |
| Spotify · YouTube Music · SoundCloud · Bandcamp · Deezer · Apple Music · Tidal · Mixcloud | YouTube · TikTok · Instagram · X (Twitter) · Facebook · Vimeo · Dailymotion · Twitch | Any **web link** supported by `yt-dlp` |

## 🚀 Features

### Downloader
- Fast downloads that keep running with the screen off, thanks to a foreground keep-alive service.
- Smart track matching and metadata tagging, with a logo and colour for each source.

### Android player
- Smooth 60 fps Jetpack Compose UI with a swipe-to-dismiss full-screen player.
- Library tabs for **Folders, Artists, Albums and Playlists**, with batch move, delete and search.
- 🚗 **Drive Mode**: a high-contrast AMOLED in-car screen with big 80 dp touch targets and swipe-to-skip.
- ⏱️ **Sleep timer**, Reels-style music video feed, and an in-app feedback hub.

### Sonixy Connect (Windows & Mac)
- 🔊 Plays whatever Sonixy is playing on your phone through your computer's speakers.
- 📡 Pair once over Wi-Fi (or scan a QR code); after that it reconnects by itself.
- 📱 Choose on the phone whether it stays silent or plays too. If the PC drops, the music pauses.
- 🛡️ Fixes Windows Firewall for you with one admin prompt, so it works on Public networks too.
- Automatic updates on Windows.

---

## 📲 Installation

<details open>
<summary><b>Android</b></summary>

1. Download [**`Sonixy-v1.4.1-code13-release.apk`**](https://github.com/nourddinak/sonixy/releases/download/v1.4.1/Sonixy-v1.4.1-code13-release.apk).
2. Open the file from your notifications or file manager.
3. Allow **"Install unknown apps"** if Android asks.
4. Open Sonixy, paste a link, and press download.

</details>

<details>
<summary><b>Windows</b></summary>

1. Download [**`Sonixy-Connect-Setup-2.0.1.exe`**](https://github.com/nourddinak/sonixy/releases/download/v1.4.1/Sonixy-Connect-Setup-2.0.1.exe).
2. Run the installer. On first launch, allow the admin prompt once so your phone can reach the PC on any network.
3. On your phone, open the player, tap the cast icon, pick your PC and click **Allow** on the PC.
4. Updates install automatically from then on.

</details>

<details>
<summary><b>Mac</b></summary>

1. Download [**`Sonixy-Connect-2.0.0-mac.dmg`**](https://github.com/nourddinak/sonixy/releases/download/v1.4.0/Sonixy-Connect-2.0.0-mac.dmg) (one file for Intel and Apple silicon).
2. Open it and drag **Sonixy Connect** into Applications.
3. The app isn't notarized by Apple, so macOS blocks the first launch: open **System Settings → Privacy & Security** and click **Open Anyway**. Then allow **Local Network** access.
4. Pair from your phone like on Windows. The Mac version doesn't update itself; download new versions from the Releases page.

</details>

---

## 🔐 Verify your download

```powershell
Get-FileHash -Algorithm SHA256 .\Sonixy-v1.4.1-code13-release.apk
```

On a Mac: `shasum -a 256 Sonixy-Connect-2.0.0-mac.dmg`

| File | SHA-256 |
| :--- | :--- |
| `Sonixy-v1.4.1-code13-release.apk` | `5D1097D9E60F2C9B0E7BB0A9169BF6CD9838B4DA39C87E4DCEC32C4A96C9A148` |
| `Sonixy-Connect-Setup-2.0.1.exe` | `D6BB45119594EC6A119D4ACD79C431E628CC7BF10077EDFD7CF6377BE42EE275` |
| `Sonixy-Connect-2.0.0-mac.dmg` | `B53694F19E2EBB69C93821C60D7472BA736A03C0293D011110977A1D56106A48` |

Hashes for older versions are in [`releases/README.md`](releases/README.md).

---

## ❓ FAQ

<details>
<summary><b>Is Sonixy free?</b></summary>
Yes. Sonixy is free to download and use, with no ads, no subscription and no account.
</details>

<details>
<summary><b>Is it on the Google Play Store?</b></summary>
Not yet. Install the APK from the <a href="https://github.com/nourddinak/sonixy/releases/latest">Releases page</a>.
</details>

<details>
<summary><b>Android says the app is from an unknown source. Is it safe?</b></summary>
That warning shows for every app installed outside the Play Store. Download only from this repo or the official website, and compare the SHA-256 hash above.
</details>

<details>
<summary><b>Is the source code available?</b></summary>
No. Sonixy is freeware: the apps are free to use, but the source code is closed. See <a href="LICENSE">LICENSE</a>.
</details>

---

## 🛠️ Built with

**Android:** Kotlin · Jetpack Compose · Media3 / ExoPlayer · Chaquopy (embedded Python) · Coroutines & Flow · Ktor · Material 3
**Desktop (Sonixy Connect):** Electron · React · Vite · WebSockets · Bonjour / mDNS
**Engine:** Python · `yt-dlp` · SpotDL resolver · Mutagen tagger

---

## ⚖️ Disclaimer

Sonixy is a tool for personal use. Respect copyright and the terms of service of the platforms you download from. Only download content you have the right to. Sonixy is not affiliated with Spotify, YouTube, or any other platform named here.

## 📄 License

Sonixy is **freeware**: free to download and use, closed source. Redistribution, resale and reverse engineering are not allowed. See [`LICENSE`](LICENSE) for the full terms.

<div align="center">

<br/>

**If Sonixy is useful to you, please ⭐ star the repo. It helps others find it!**

Made with ❤️ by [nourddinak](https://github.com/nourddinak)

</div>
