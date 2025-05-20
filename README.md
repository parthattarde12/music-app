# SonicVibe: Offline Music Player

SonicVibe is a fully-featured offline music player for Android built with Flutter. Play your local music with a modern, beautiful interface and powerful features.

## Features

- **Local Music Playback**: Play MP3 files from your device with high-quality audio
- **Background Playback**: Keep your music playing even when the app is minimized
- **Media Controls**: Control playback from your notification shade
- **Playlist Management**: Create, edit, and manage your playlists
- **Beautiful UI**: Enjoy a modern Material 3 design with both Light and Dark themes
- **Song Info**: View and sort by title, artist, and album art
- **Playback Controls**: Shuffle, repeat, skip, seek, and volume controls

## Getting Started

### Prerequisites

- Flutter 3.0 or higher
- Android 5.0+ (API level 21+) device or emulator

### Installation

1. Clone the repository
2. Install dependencies
   ```
   flutter pub get
   ```
3. Run the app
   ```
   flutter run
   ```

### Permissions

On first launch, the app will request storage permissions to access your music files. These permissions are essential for the app to function.

## Usage

### Importing Music

- The app automatically scans and displays music from your device storage
- Tap the floating action button to manually select and import specific audio files

### Playback

- Tap on any song to start playback
- Use the mini-player at the bottom of the screen for quick controls
- Tap on the mini-player to open the full Now Playing screen

### Playlists

- Navigate to the Playlists tab to create and manage playlists
- Add songs to playlists for easy access

## Architecture

SonicVibe is built with:

- **Flutter**: UI framework
- **GetX**: State management and navigation
- **just_audio**: Audio playback engine
- **on_audio_query**: Media store query provider
- **permission_handler**: Permission management
- **file_picker**: File selection

## License

This project is licensed under the MIT License - see the LICENSE file for details.
