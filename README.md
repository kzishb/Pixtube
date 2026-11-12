# Pixtube

A privacy-respecting YouTube and YouTube Music client for Android, with a recommendation engine that runs entirely on your phone.

Pixtube is a personal fork of [Flow](https://github.com/Flow-Tube/Flow) by A-EDev, customized by Kazi Shihab Uddin. It has its own name, icon and default theme, and it installs next to Flow as a separate app.

## Features

- Video playback with resolution switching, background playback, Picture-in-Picture and casting
- SponsorBlock, DeArrow and Return YouTube Dislike
- YouTube Music with queue, lyrics and a mini player
- On-device recommendations: no account, no tracking, no ads
- Local history, favorites, playlists, Shorts and subscriptions
- Downloads, NewPipe import, backup and restore
- Many themes; the default is a deep night theme with a violet accent

## Build the APK (no setup on your computer)

1. Open the **Actions** tab of this repository.
2. Choose **Build Pixtube APK** and press **Run workflow**.
3. When it finishes, open the run and download the **pixtube-apk** artifact.
4. Unzip it and install `app-github-arm64-v8a-release.apk` on most phones, or `app-github-universal-release.apk` if you are not sure.

The APK is signed with a debug key, so each new build must be installed after removing the previous one. Automatic updates are turned off.

## License and credits

Pixtube is free software under the **GNU General Public License v3 (GPLv3)**, the same license as Flow. See the `License` file.

- Original work: Copyright © 2025-2026 A-EDev (Flow)
- Modifications: Copyright © 2026 Kazi Shihab Uddin

Flow itself builds on NewPipeExtractor, NewPipe, PipePipe, Metrolist, LibreTube, ExoPlayer, Jetpack Compose and Material Design 3. Thanks to everyone behind those projects.

Source code for every build is available in this repository.
