# Sonixy Releases

## v1.4.1

- File: `Sonixy-v1.4.1-code13-release.apk` (also `Sonixy-v1.4.1-code13-release.aab`)
- Version name: `1.4.1`
- Version code: `13`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `5D1097D9E60F2C9B0E7BB0A9169BF6CD9838B4DA39C87E4DCEC32C4A96C9A148`

**Sonixy Connect 2.0.1** (Companion for Windows and Mac)
- Windows: `Sonixy-Connect-Setup-2.0.1.exe`, auto-updater `latest.yml`
  - SHA-256: `D6BB45119594EC6A119D4ACD79C431E628CC7BF10077EDFD7CF6377BE42EE275`

### Release Notes

Sonixy v1.4.1 introduces automatic offline mode detection, fluid swipe-down-to-refresh across the music library, and a redesigned desktop interface for Sonixy Connect matching the mobile app's frosted glass aesthetic.

- **Auto Offline Mode**: When Wi-Fi and cellular connections drop, Sonixy automatically transitions to offline mode, moves you to your local library, and disables network-bound operations. When connectivity returns, the app seamlessly restores full online features and returns you to Home.
- **Library Swipe-Down-To-Refresh**: Added spring-physics pull-to-refresh across all library tabs (Playlists, Songs, Artists, Favorites) and playlist/artist detail screens. Non-passive touch interception guarantees smooth gesture tracking without browser interruption, complete with haptic feedback.
- **Redesigned Sonixy Connect 2.0.1 (Desktop)**: Brand-new companion interface styled with Sonixy's signature frosted glass, matching soft 3D phone artwork, animated album art backdrop blur, custom progress & volume sliders, and cleaner pairing instructions.

## v1.4.0

- File: `Sonixy-v1.4.0-code12-release.apk` (also `Sonixy-v1.4.0-code12-release.aab`)
- Version name: `1.4.0`
- Version code: `12`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `232BFC5D838A85577062CA16A8CB135847588501AD7EC288BDC27092D723CA4A`

**Sonixy Connect 2.0.0** (replaces Sonixy Desktop; Desktop users are updated automatically)
- Windows: `Sonixy-Connect-Setup-2.0.0.exe`, auto-updater `latest.yml`
  - SHA-256: `D1A41287150CCEF0486BC5EF8A93027A3AC8C850B3B8A136D9E07F58A17F40F9`
- Mac (universal: Intel & Apple silicon, macOS 12+): `Sonixy-Connect-2.0.0-mac.dmg`, built by the *Build Sonixy Connect for Mac* workflow
  - SHA-256: `B53694F19E2EBB69C93821C60D7472BA736A03C0293D011110977A1D56106A48`

### Release Notes

Sonixy v1.4.0 brings Sonixy Connect, a new small app for Windows and Mac that plays your phone's Sonixy music through your computer.

- **Sonixy Connect**: pair once (allow the phone on the PC, or scan a QR code), then it reconnects by itself on the same Wi-Fi. Choose on the phone whether it stays silent or plays too; if the PC drops, the music pauses. Fixes Windows Firewall with one admin prompt so it also works on Public networks. Phones need v1.4.0 to pair.
- **More download sources**: YouTube Music, SoundCloud, Bandcamp, Deezer, Apple Music, Tidal, TikTok, Instagram, X, Facebook, Vimeo, Dailymotion, Twitch, Mixcloud and more; playlists and albums expand into full track lists.
- **Redesigned downloader page** with real platform logos and a smooth scrolling platform row.
- **Library fixes**: All Songs plays through your whole library, songs load right away after an update, artist pictures download for every artist, and images no longer flash.
- **Removed** the old desktop extras (export to PC, lyrics on PC, Discord status).

## v1.3.1

- File: `releases/sonixy-v1.3.1-release-signed.apk`
- Version name: `1.3.1`
- Version code: `11`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `D7D393705B1B87F1FDD0134897AA72526734514672D6D9793A73B5322EB9039F`

**Desktop Companion** (unchanged)
- File: `releases/desktop/Sonixy-Desktop-Setup-1.2.6.exe`
- Auto-Updater: `releases/desktop/latest.yml`
- SHA-256: `5739372F94AFCE120A00BC7C1BA233A402DFF077CD74E6FDC98825CBD8E94DC6`

### Release Notes

Sonixy v1.3.1 widens where you can pull music from, with branded source pickers and downloader improvements.

- **More Source Platforms**: YouTube Music, Bandcamp, Deezer, Apple Music, Tidal, Mixcloud, TikTok, Instagram, X, Facebook, Vimeo, Dailymotion and Twitch, plus a "Web link" option for any site yt-dlp supports.
- **Platform Logos**: Each source shows its own logo and colour in the downloader.
- **Downloader & Library Fixes**: Improvements to the download engine, the YouTube path and the library screens.

## v1.3.0

- File: `releases/sonixy-v1.3.0-release-signed.apk`
- Version name: `1.3.0`
- Version code: `10`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `930709D99A124FE09F10A9787E8E05013036110D7350A1DA67C6C436841E0708`

**Desktop Companion**
- File: `releases/desktop/Sonixy-Desktop-Setup-1.2.6.exe`
- Auto-Updater: `releases/desktop/latest.yml`
- SHA-256: `5739372F94AFCE120A00BC7C1BA233A402DFF077CD74E6FDC98825CBD8E94DC6`

### Release Notes

Sonixy v1.3.0 introduces Drive Mode, an enhanced multi-view Library experience, a background download keep-alive service, an in-app feedback hub, and local network pairing with Desktop.

- **Drive Mode Overlay**: Safe, high-contrast AMOLED in-car UI with oversized 80dp touch targets, instant swipe controls, and glanceable track info for hands-free listening.
- **Enhanced Library Navigation**: Redesigned library tabs with dedicated Folders, Artists, Albums, and Playlist filtering for effortless offline collection management.
- **Background Download Keep-Alive Service**: Persistent foreground service keeps downloads running uninterrupted even during deep battery optimization and device sleep.
- **In-App Feedback Hub**: Built-in support to report issues, suggest features, and view diagnostic logs without leaving the app.
- **Sleep Timer & Desktop LAN Sync**: Set bedtime playback countdowns and seamlessly cast/sync playback state with Sonixy Desktop on your local Wi-Fi.

## v1.2.6

- File: `releases/sonixy-v1.2.6-release-signed.apk`
- Version name: `1.2.6`
- Version code: `9`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `0856C348CE725A8E022C62B18638DFA0974F0B3429F57AEFC2CCE1A067723200`

**Desktop Companion**
- File: `releases/desktop/Sonixy-Desktop-Setup-1.2.6.exe`
- Auto-Updater: `releases/desktop/latest.yml`
- SHA-256: `5739372F94AFCE120A00BC7C1BA233A402DFF077CD74E6FDC98825CBD8E94DC6`

### Release Notes

Sonixy v1.2.6 introduces a massive performance overhaul to the mobile library, a premium UI redesign, and a dynamic floating mini player.

- **Super Performance**: Completely rewrote the Library list architecture, ripping out custom paging in favor of pure native Jetpack Compose virtualization and aggressive Coil image caching. Massive libraries now scroll effortlessly at 120fps with zero lag.
- **Premium Glassmorphism UI**: Introduced sleek translucent gradient headers, ExtraBold modern typography, and beautifully rounded track cards for a high-end feel.
- **Floating Pill Mini Player**: Replaced the docked player bar with a gorgeous floating pill that dynamically adapts to your selected theme (Light/Dark/AMOLED) with a stunning, context-aware glowing drop shadow.

## v1.2.5

- File: `releases/sonixy-v1.2.5-release-signed.apk`
- Version name: `1.2.5`
- Version code: `8`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `76CA1012EF03AC609EEAAE1D05F0F0FD8EE088ABA13F6E92B856953B8FC099CF`

**Desktop Companion**
- File: `releases/desktop/Sonixy-Desktop-Setup-1.2.4.exe`
- Auto-Updater: `releases/desktop/latest.yml`
- SHA-256: `41C993C7976E6D7FAB6F52C13598F3054153D930D11B1AA3C04BE403B1CB13B9`

### Release Notes

Sonixy v1.2.5 brings major UI performance enhancements, ultra-smooth player overlay transitions, full isolation for background media, and a redesigned Settings & Update hub.

- **Zero-Stutter Player Overlay**: Completely eliminated open/close lag by removing full-hierarchy recompositions and utilizing hardware-accelerated `Modifier.graphicsLayer` transforms with fluid spring physics.
- **Reels Background & Viewport Fix**: Resolved reels playing when off-screen or peeking into neighboring tabs.
- **Modernized Settings & Update Hub**: Reorganized Settings with prominent in-app App & Python Engine update cards at the top, storage breakdown, and diagnostics.
- **Icon Modernization & Performance**: Updated navigation, playback, and volume icons to AutoMirrored standards and stripped redundant animation wrappers.

## v1.2.4

- File: `releases/sonixy-v1.2.4-release-signed.apk`
- Version name: `1.2.4`
- Version code: `7`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `16E0730643B1342773995E05FBED94C2FF4F0B6A0FF4595FC287DBCDE61FE955`

### Release Notes

Sonixy v1.2.4 contains minor updates and bug fixes.

## v1.2.3

- File: `releases/sonixy-v1.2.3-release-signed.apk`
- Version name: `1.2.3`
- Version code: `6`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `8DCE6594B32081D5E64916706227862676935F3B6908F493EF8EE8551C411C9B`

**Desktop**
- File: `releases/desktop/Sonixy Desktop Setup 1.2.3.exe`
- Auto-Updater: `releases/desktop/latest.yml`

### Release Notes

Sonixy v1.2.3 brings a major overhaul to the Discover Home tab and Onboarding experience, prioritizing ultra-smooth 60fps performance and premium aesthetics.

- Completely rebuilt the Home screen with a new decoupled layout architecture to guarantee zero-lag scrolling and eliminate startup lag.
- Added Global Region filters (Country and Category chips) to the top of the Home feed to instantly discover trending tracks globally.
- Redesigned the main track card into a premium glassmorphic `PremiumTrackCard` with micro-animations.
- Upgraded the Onboarding flow with dynamic content, fluid "breathing" background art, and newly designed premium mock track cards.
- Restyled the `PreviewMiniPlayer` to flawlessly integrate above the global navigation bar.
- Removed all implicit layout nesting bugs that previously caused dropped frames during complex layout evaluations.

## v1.2.2

- File: `releases/sonixy-v1.2.2-release-signed.apk`
- Version name: `1.2.2`
- Version code: `5`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `8853818C20266B32FA210E7392295E1C9647E0FCD4643A638A0C6B2A5BDBF7DD`

### Release Notes

Sonixy v1.2.2 is a visual polish release for the player, library, onboarding, and responsive layouts.

- Added first-install and update onboarding screens that introduce Sonixy and highlight what changed after updates.
- Redesigned the full now-playing overlay with a larger animated cover, smooth wavy progress ring, cleaner controls, and a logo-style scrubber thumb.
- Added a compact Next Song panel with artist artwork, multi-artist support, and a clearer bottom placement.
- Added current-song artist visuals under the title so featured artists feel connected to the playing track.
- Redesigned the volume and sleep timer overlays with theme-aware colors and cleaner icon-led controls.
- Added Favorite Artists support, including a picker page where users can select artists and pin them at the top of the Artists page.
- Improved library, folder, and artist pages with cleaner outlines, smoother search styling, better spacing, full-width banner artwork, and softer image-to-list fades.
- Improved artist image quality and fixed header icon placement on the Artists page.
- Fixed responsive sizing issues across small and large phones, including search text visibility and player spacing.
- Fixed the Downloader page light theme so the Download action remains visible in white mode.

## v1.2.1

- File: `releases/sonixy-v1.2.1-release-signed.apk`
- Version name: `1.2.1`
- Version code: `4`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `F4981246879C4FF4027F055F2EC4467D990507C59B27AC226749B5B680F6A384`

### Release Notes

Sonixy v1.2.1 focuses on a dedicated, distraction-free Offline Mode experience with refined navigation and a floating mini-player, alongside smoother app loads and new features.

- Added the Reels tab to deliver an immersive and interactive music shorts feed.
- Optimized app launching and transition mechanics to make app loads significantly smoother.
- Refactored Offline Mode to keep only the Library page, removing other tabs when offline.
- Completely hid the bottom navigation bar when in Offline Mode for a cleaner experience.
- Repositioned the bottom mini-player (expanded and collapsed modes) to float elegantly at the bottom nav area when offline.
- Updated the back button handler to correctly warn and exit the app from the Library page when offline, instead of forcing navigation to the hidden Home page.

## v1.2

- File: `releases/sonixy-v1.2-release-signed.apk`
- Version name: `1.2`
- Version code: `3`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `0100C3F212CFEB18EC1856C51A1ACEA6095129FA4319DD6101F36D4DF790B54B`

### Release Notes

Sonixy v1.2 improves lyrics recovery, library organization, and the collapsed player experience.

- Added a virtual `No Lyrics` library folder for songs that do not have saved `.lrc` or `.txt` lyrics yet.
- Added lyrics search actions inside folder pages so users can find and save lyrics for a whole folder, selected songs, or one song.
- Added metadata-based lyrics lookup for local songs using their saved artist and title.
- Improved LRCLib search matching with cleaned titles, title-only fallback, and better candidate handling.
- Added detailed lyrics debug logs for LRCLib rows, picked lyrics, HTTP errors, timeouts, and save results.
- Fixed lyrics search so it stops waiting on slower candidate lookups after a good match is found.
- Fixed LRCLib exact lookup so plain lyrics are accepted when synced lyrics are not returned.
- Redesigned the collapsed bottom mini-player into a slim text rail with marquee title, compact controls, and a thin progress line.
- Removed the incompatible `syncedlyrics` Python dependency so Android release builds do not fail on missing `rapidfuzz` wheels.
- Kept Genius removed because it requires API access and is not a free no-token provider.

## v1.1

- File: `releases/sonixy-v1.1-release-signed.apk`
- Version name: `1.1`
- Version code: `2`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `B3E9DDB1231015DA9F8B5009277E4DD641A283B668A339D9BF02AD8B2078D6A9`

### Release Notes

Sonixy v1.1 adds a built-in app updater, smoother library behavior, and a cleaner now-playing experience.

- Added an in-app update option in Settings that checks the latest GitHub release.
- Added APK downloading with progress so users can update directly from inside Sonixy.
- Added installer launch support after an update APK finishes downloading.
- Improved the Library page so automatic reloads happen quietly in the background.
- Kept loading animations only for manual actions like tapping refresh or pulling to refresh.
- Fixed playlist/folder overlays so taps no longer go through to items behind the open folder.
- Added visual feedback for folder Play All and Shuffle actions.
- Fixed Play All so it turns shuffle off and plays the folder in order.
- Fixed Shuffle so it starts folder playback with shuffle enabled.
- Fixed cover cleanup so deleting a song from one folder does not remove its cover if the same song still exists in another folder.
- Improved the now-playing overlay layout with wider title text, better lyrics spacing, and fuller playback controls.

## v1.0

- File: `releases/sonixy-v1.0-release-signed.apk`
- Version name: `1.0`
- Version code: `1`
- Application ID: `com.nourddinak.sonixy`
- SHA-256: `B973FBF07AD4EC28B54B396F2EDD44D81E676FF4C3FE7EABFD0164C99C46CA7E`

### Release Notes

- Initial packaged APK release.
- Includes Spotify link handling, download flow, metadata lookup, lyrics support, and local playback.
- This is a signed release build.
