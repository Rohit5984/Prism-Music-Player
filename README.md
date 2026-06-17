# Prism Music Player

![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-blue)
![Flutter](https://img.shields.io/badge/Built%20With-Flutter-02569B)
![License](https://img.shields.io/badge/License-MIT-green)

A modern, high-performance desktop music player for Windows, built with Flutter.

Prism Music Player focuses on speed, simplicity, and broad audio format support. It automatically discovers your music library, supports advanced playback controls, and allows instant playback by opening audio files directly from Windows Explorer.

---

## Preview

> Add screenshots or GIFs here.

### Library View

![Library Screenshot](assets/screenshots/library.png)

### Now Playing

![Player Screenshot](assets/screenshots/player.png)

---

## Features

| Feature              | Description                                                                                                                               |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Audio Format Support | Supports 20+ formats including MP3, WAV, FLAC, OGG, AAC, M4A, WMA, OPUS, AIFF, APE, WEBM, 3GP, OGA, WV, AMR, MID, MIDI, MKA, DTS, and AC3 |
| Smart Library        | Automatically scans Music, Downloads, and Desktop folders                                                                                 |
| Queue Management     | Drag-and-drop queue reordering                                                                                                            |
| Shuffle & Repeat     | Multiple playback modes                                                                                                                   |
| Sleep Timer          | 15, 30, 45, and 60-minute presets                                                                                                         |
| Playback Speed       | Adjustable speed from 0.5× to 2.0×                                                                                                        |
| Crossfade            | Smooth transitions between tracks                                                                                                         |
| Full-Screen Player   | Album artwork and animated visualizer                                                                                                     |
| Keyboard Shortcuts   | Fast playback and navigation controls                                                                                                     |
| File Association     | Open supported audio files directly with Prism                                                                                            |
| Single Instance Mode | Refocuses existing window instead of launching duplicates                                                                                 |

---

## Supported Audio Formats

* MP3
* WAV
* FLAC
* OGG
* AAC
* M4A
* WMA
* OPUS
* AIFF
* APE
* WEBM
* 3GP
* OGA
* WV
* AMR
* MID
* MIDI
* MKA
* DTS
* AC3

---

## Installation

### Download

Download the latest installer from the **Releases** page.

### Requirements

* Windows 10 (64-bit) or later
* Windows 11
* Approximately 50 MB of free disk space

### Install

1. Download the latest release.
2. Run the installer.
3. Launch Prism Music Player.
4. Double-click any supported audio file to start listening.

---

## Build From Source

### Prerequisites

* Flutter SDK
* Dart SDK
* Windows Desktop Development tools

### Clone Repository

```bash
git clone https://github.com/your-username/prism-music-player.git
cd prism-music-player
```

### Install Dependencies

```bash
flutter pub get
```

### Run in Debug Mode

```bash
flutter run -d windows
```

### Build Release Version

```bash
flutter build windows --release
```

---

## Keyboard Shortcuts

| Shortcut    | Action             |
| ----------- | ------------------ |
| Space       | Play / Pause       |
| Left Arrow  | Seek Backward      |
| Right Arrow | Seek Forward       |
| Up Arrow    | Volume Up          |
| Down Arrow  | Volume Down        |
| Ctrl + Q    | Toggle Queue       |
| Ctrl + F    | Toggle Full Screen |
| Ctrl + S    | Toggle Shuffle     |

---

## Tech Stack

* Flutter
* Dart
* just_audio
* audio_service
* provider
* win32

---

## Roadmap

* [ ] Equalizer
* [ ] Lyrics Support
* [ ] Playlist Import/Export
* [ ] Theme Customization
* [ ] Last.fm Integration
* [ ] Cloud Sync

---

## Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

---

## Credits

Made with ❤️ by:

* Rohit Mandal — Lead Developer
* Sushant Chy
* Bishal Chy
* Gopal Gupta

---

## License

Distributed under the MIT License.

See the `LICENSE` file for more information.
