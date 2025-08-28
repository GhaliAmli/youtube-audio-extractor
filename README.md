# youtube-audio-extractor

A simple, open-source Python tool to download audio from YouTube videos and convert it to MP3. Designed for learning, experimentation, and personal use. Works entirely from the terminal.

---

## Features

* Download audio from any YouTube video.
* Convert audio to MP3 automatically.
* Terminal-friendly and lightweight.
* Open-source and educational.

---

## Prerequisites

* Python 3.x
* [ffmpeg](https://ffmpeg.org/) installed and added to your PATH.

Install Python packages:

```bash
pip install pytube pydub
```

Install `ffmpeg`:

* **Linux**:

```bash
sudo apt install ffmpeg
```

* **Mac**:

```bash
brew install ffmpeg
```

* **Windows**: Download from [ffmpeg.org](https://ffmpeg.org/) and add to PATH.

---

## Usage

1. Clone the repository or download the script.
2. Run the script in the terminal:

```bash
python3 extract.py
```

3. Enter the YouTube video URL when prompted.
4. The MP3 file will be saved in the current folder.

---

## Example

```bash
Enter YouTube URL: https://www.youtube.com/watch?v=example
Downloading: My Favorite Song
Download completed.
MP3 file created: My Favorite Song.mp3
Temporary file removed.
```

---

## License

This project is open-source and free to use for learning and experimentation purposes. Please respect copyright laws and do not distribute copyrighted material.
