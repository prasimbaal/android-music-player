# Audio Player Android App

## Overview

Welcome to the Audio Player Android App! This application is a simple, user-friendly audio player built using Kotlin. It allows users to play audio files stored on their device, providing a sleek interface and basic playback functionalities.

## Features

- **Play/Pause/Stop**: Control audio playback with intuitive buttons.
- **Seek Bar**: Navigate through the audio track using a seek bar.
- **File Selection**: Browse and select audio files from the device's storage.
- **Playback Notifications**: Receive playback controls in the notification bar.
- **Background Play**: Continue audio playback while using other apps.
- **Playlist Management**: Create and manage playlists for organized listening.

## Screenshots

<!-- Add screenshots of your app here -->
![Home Screen](screenshots/home_screen.png)
![Playback Screen](screenshots/playback_screen.png)

## Installation

To run this app on your Android device:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/prasimbaal/android-music-player.git
   cd audioplayer
    Open in Android Studio:
        Launch Android Studio.
        Select "Open an existing Android Studio project".
        Navigate to the cloned repository and open it.

    Build and Run:
        Connect your Android device via USB or use an emulator.
        Click on the "Run" button in Android Studio.

Usage

    Select an Audio File: Use the file browser to locate and select an audio file from your device.
    Control Playback:
        Play/Pause: Use the play/pause button to control the audio.
        Stop: Use the stop button to halt playback.
        Seek: Drag the seek bar to navigate through the audio track.
    Notifications: Control playback directly from the notification bar.
    Background Playback: Continue listening to your audio while using other apps.

Code Structure

    MainActivity.kt: Handles the main user interface and interactions.
    MusicService.kt: Manages the audio playback in the background.
    SongAdapter.kt: Contains the core audio playback logic.

Dependencies

    MediaPlayer: Android's built-in media player for audio playback.
    FilePicker: Library for browsing and selecting files.
    KSP(Kotlin Symbol Processing) : for faster kotlin code processing.
    Glide: for fast and efficient image loading library for Android focused on smooth scrolling
    Kotlin Coroutines: For asynchronous operations and background tasks.

Contributing

We welcome contributions to enhance the app's functionality and user experience. To contribute:

    Fork the repository.
    Create a new branch with a descriptive name.
    Make your changes and commit them.
    Push your branch to your forked repository.
    Create a pull request with a detailed description of your changes.
