# Audio Joiner

A single-page web app that combines several audio files (MP3, WAV, OGG, M4A and other formats your browser can play) into one soundtrack, with silence between songs.

## Features
- Choose multiple files, mix formats freely, reorder with ↑ / ↓, remove any you don't want
- Silence between songs: 2, 2.5 or 3 seconds (default 3), or a custom length (0-60 s)
- Optional 2-second fade-out / fade-in around each gap
- Export as MP3 (128-320 kbps) or WAV
- Editable output file name (Vietnamese names work)
- Preview, Download, and Share (iPhone share sheet)
- Runs entirely in the browser; no files are uploaded

## Supported inputs
Whatever the browser can decode. MP3, WAV and M4A/AAC work everywhere; OGG/Opus and FLAC depend on the browser version (older Safari may skip OGG). Unsupported files are skipped with a message.

## Files
- `index.html` - the whole app
- `audio-joiner-icon.png` - 180x180 Home Screen icon (add this file next to index.html)

## Publish on GitHub Pages
1. Put `index.html` and `audio-joiner-icon.png` in the repo and **commit** both.
2. Wait 1-2 minutes for Pages to update.
3. On iPhone: delete any old shortcut, quit Safari, reload the page, then Share → Add to Home Screen.

Note: MP3 encoding uses lamejs loaded from a CDN, so the first load needs internet.
