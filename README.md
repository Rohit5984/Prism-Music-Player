🎵 Prism Music Player
A modern, high-performance desktop music player for Windows — built with Flutter.

Double-click any audio file and start listening instantly.






📸 Preview
(Add a screenshot of your player here — library view with a song playing)

✨ Features
	
🎶 20+ Audio Formats	MP3, WAV, FLAC, OGG, AAC, M4A, WMA, OPUS, AIFF, APE, WEBM, 3GP, OGA, WV, AMR, MID, MIDI, MKA, DTS, AC3
📂 Smart Library	Auto-scans Music, Downloads, Desktop folders
🔀 Queue & Shuffle	Drag-to-reorder, repeat modes, shuffle
⏱ Sleep Timer	15 / 30 / 45 / 60 min
⏩ Playback Speed	0.5x – 2.0x
🎨 Full-screen Player	Animated visualizer, album art
🎚 Crossfade	Smooth track transitions
⌨️ Keyboard Shortcuts	Play, seek, volume, queue toggle
📁 File Association	Double-click any audio file to play
🪟 Single Instance	Re-focuses existing window instead of opening a new one


⚡ Quick Start
Download
Grab the latest installer from the Releases page.
Requirements: Windows 10 / 11 (64-bit), ~50 MB disk space.
Build from Source
flutter pub get
flutter build windows --release

Binary output: build\windows\x64\runner\Release\music_player.exe
Prerequisites: Flutter SDK (stable), Visual Studio 2022 with Desktop development with C++ workload.

⌨️ Keyboard Shortcuts
Key	Action
Space	Play / Pause
←→	Seek ±5s
Ctrl + ←	Previous track
Ctrl + →	Next track
Ctrl + ↑	Volume up
Ctrl + ↓	Volume down
M	Mute / Unmute
S	Toggle shuffle
R	Cycle repeat mode
L	Toggle queue panel


🛠 Tech Stack
·	Framework: Flutter 3.44+ (Dart 3.12)
·	Audio Engine:just_audio
·	Window Management:window_manager
·	Platform: Windows 64-bit (C++/Win32)

👥 Credits
Made with ❤️ by
·	Rohit Mandal — Lead Developer
·	Sushant Chy
·	Bishal Chy
·	Gopal Gupta
AppCrafted

📄 License
Distributed under the MIT License. See LICENSE for more information.
