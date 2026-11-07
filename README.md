# KN Woodwinds Transcription Player

A free app for transcribing music by ear, made for woodwind players.

## Download

| Device | Download |
| --- | --- |
| **Windows** | [Installer (recommended)](https://github.com/knwoodwinds/The-KN-Woodwinds-Transcription-Software/releases/latest/download/KN-Woodwinds-Transcription-Player-Setup.exe) or the [portable version](https://github.com/knwoodwinds/The-KN-Woodwinds-Transcription-Software/releases/latest/download/KN-Woodwinds-Transcription-Player-Portable.exe) (no install needed) |
| **Android** | [KN-Woodwinds-Transcription-Player.apk](https://github.com/knwoodwinds/The-KN-Woodwinds-Transcription-Software/releases/latest/download/KN-Woodwinds-Transcription-Player.apk) |

These links always give you the newest version. All versions are on the [Releases page](https://github.com/knwoodwinds/The-KN-Woodwinds-Transcription-Software/releases).

### Installing on Windows
Run the file you downloaded. Windows may show a blue "Windows protected your PC" box because the app is not digitally signed. Click **More info**, then **Run anyway**.

### Installing on Android
1. Open the link above on your phone and keep the download if Chrome warns about it.
2. Open the file. When Android says it can't install unknown apps from your browser, tap **Settings**, turn on **Allow from this source**, and go back.
3. Tap **Install**. If Play Protect warns about an unknown app, tap **More details**, then **Install anyway**.

## What it does

- **Slow down without changing pitch** (10% to 150%)
- **Hold to freeze a note** so you can match it on your instrument
- **A-B loop**: drag on the waveform to select a passage and it loops
- **Waveform view**: click to jump anywhere, zoom with the mouse wheel or pinch, scroll with Shift+wheel or two fingers, drag selection edges to fine-tune
- **Trim tool**: keep or cut a selection (Delete key), undo, save as WAV
- **Saved loops** remembered per song
- **Tempo detection**
- **Metronome** (tap tempo, match the song's tempo) and **tuner** (microphone, bar or dial display, transposition for clarinet and saxophones)
- Customizable keyboard shortcuts, tuner range, zoom and waveform size
- Several color themes (Options menu)
- Works without an internet connection. Your music never leaves your device.

## Build it yourself

Windows: install Node.js, then in this folder run `npm install` and `npm run build`. The installers appear in the `dist` folder.

Android: see `.github/workflows/android.yml`. GitHub builds the APK automatically when a release is published.
