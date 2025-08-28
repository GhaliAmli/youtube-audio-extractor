# youtube-audio-extractor

A simple, open-source Python tool to download audio from YouTube videos and convert it to MP3 using `yt-dlp`. Designed for learning, experimentation, and personal use. Works entirely from the terminal.

---

## Features

- Download audio from any YouTube video.
- Convert audio to MP3 automatically.
- Handles complex YouTube URLs and playlists.
- Terminal-friendly and lightweight.
- Open-source and educational.

---

## Prerequisites

- Python 3.x  
- [ffmpeg](https://ffmpeg.org/) installed or specify its path in the script.

Install required Python packages:  
```bash
pip install yt-dlp
```

Install `ffmpeg`:

- **Windows:** Download from [ffmpeg.org](https://ffmpeg.org/) → extract → add `bin` folder to PATH, or use the path in the script.
- **Linux:** `sudo apt install ffmpeg`
- **Mac:** `brew install ffmpeg`

---

## Usage

1. Clone the repository or download the script.
2. Run the script in the terminal:

```bash
python extract.py
```

3. Enter the YouTube video URL when prompted.
4. The MP3 file will be saved in the current folder (or output folder if configured).

### Example

```bash
Enter YouTube URL: https://youtu.be/jNQXAC9IVRw
Downloading: Me at the zoo
Conversion to MP3 completed.
```

---

## Notes

- If you get an ffmpeg error, either install ffmpeg and add it to PATH or set `ffmpeg_location` in the script to point to your ffmpeg executable.
- This tool is meant for personal use and educational p