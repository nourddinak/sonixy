# Sonixy Releases

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
