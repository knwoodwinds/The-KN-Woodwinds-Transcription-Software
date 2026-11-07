# KN Woodwinds Transcription Player

A simple desktop app for transcribing music by ear.

- **Slow down without changing pitch** (10% to 150%)
- **Hold to freeze a note** so you can match it on your instrument
- **A-B loop**: drag on the waveform to select a passage and it loops
- **Waveform view**: click to jump anywhere, zoom with the mouse wheel, scroll with Shift+wheel, drag selection edges to fine-tune
- Press **Delete** to cut the selected passage (Ctrl+Z undoes)
- **Trim tool**: keep or cut a selection, undo, save as WAV
- **Saved loops** remembered per song
- **Key and tempo detection**
- **Metronome** (tap tempo, match the song's tempo) and **tuner** (microphone, with transposition for clarinet and saxophones; can be shown on the main screen from the Options menu)
- Adjustable tuner tolerance, zoom depth, zoom speed and waveform height (tuner and Options menu), remembered between sessions
- Customizable keyboard shortcuts for loop and trim (Options menu)
- Tuner display: bar or dial, like a clip-on tuner (Options menu)
- Several color themes (Options menu)

## Install (Windows)

1. Open the **Releases** page of this repository (right-hand side of the main page).
2. Download **KN-Woodwinds-Transcription-Player-Setup-x.x.x.exe** and run it.
   (Prefer no install? Download the **Portable** file instead and just double-click it.)
3. Windows may show a blue "Windows protected your PC" box because the app is not digitally signed.
   Click **More info**, then **Run anyway**.

## Keyboard shortcuts

Space play/pause, F (hold) freeze, A / B set loop points, L loop on/off, arrow keys jump and change speed.

## Build it yourself

Install Node.js, then in this folder run `npm install` and `npm run build`. The installers appear in `dist/`.

## Android

Download **KN-Woodwinds-Transcription-Player.apk** from the Releases page on your phone, open it, and allow installs from your browser when Android asks. The app works offline.
The Android version is built automatically from the same code. See `.github/workflows/android.yml`.
