# Sonixy Releases

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
