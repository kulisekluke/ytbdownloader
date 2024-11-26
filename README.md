# YouTube Downloader

## Overview

This program is a simple **YouTube downloader** designed to download videos and audio from various platforms (such as YouTube, Instagram Reels etc.). Created by **Kulíšek** with Python, it uses the `yt_dlp` library for downloading content in the best available quality. The program allows you to choose between downloading videos in MP4 format or audio in MP3 format. Additionally, it supports multiple downloads in one session for convenience.

This executable is packaged in a zip archive for easy distribution.

---

## Features

- Download videos or audio from supported websites like YouTube, Instagram Reels, Phub, etc.
- Supports downloading the best quality MP4 video or MP3 audio.
- Option to download multiple items in one session.
- Simple, text-based user interface for easy operation.

---

## Requirements

- **FFmpeg** (Recommended): FFmpeg is recommended for the best quality download experience. You can download it from the official website: [FFmpeg Download](https://ffmpeg.org/download.html). Make sure FFmpeg is installed and available in your system's PATH for best performance.
- **yt-dlp**: This program uses `yt-dlp`, a powerful tool for downloading videos from the web. The EXE file in the archive already includes the necessary dependencies.

---

## How to Use

1. **Extract the archive**: First, extract the contents of the zip archive to a folder on your computer.
   
2. **Run the EXE file**: Double-click the `.exe` file to run the program. The program will open in a console window.

3. **Choose download option**:
   - You will be prompted with a question asking if you want to download multiple videos/audio files. Type `y` to download more than one, or `n` to download just a single file.
   
4. **Select your download format**:
   - You will be asked to select the format:
     1. **Best Quality (MP4)** – Downloads the video in the highest available quality.
     2. **Only Audio (MP3)** – Downloads the best available audio.

5. **Enter the URL**:
   - You will then be asked to input the URL of the video/audio you wish to download.
   - If you chose to download multiple files, the program will prompt you for additional URLs.

6. **Enjoy your download**: The program will download the video/audio in the format you chose, saving it to the current directory.

---

