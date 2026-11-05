# Transcription Player

A simple desktop app for transcribing music by ear.

- **Slow down without changing pitch** (10% to 150%)
- **Hold to freeze a note** so you can match it on your instrument
- **A-B loop**: drag on the waveform to select a passage and it loops
- **Waveform view**, click to jump anywhere
- **Trim tool**: keep or cut a selection, undo, save as WAV
- **Saved loops** remembered per song
- **Key and tempo detection**
- Several color themes (Options menu)

## Install (Windows)

1. Open the **Releases** page of this repository (right-hand side of the main page).
2. Download **Transcription-Player-Setup-x.x.x.exe** and run it.
   (Prefer no install? Download the **Portable** file instead and just double-click it.)
3. Windows may show a blue "Windows protected your PC" box because the app is not digitally signed.
   Click **More info**, then **Run anyway**.

## Keyboard shortcuts

Space play/pause, F (hold) freeze, A / B set loop points, L loop on/off, arrow keys jump and change speed.

## Build it yourself

Install Node.js, then in this folder run `npm install` and `npm run build`. The installers appear in `dist/`.
