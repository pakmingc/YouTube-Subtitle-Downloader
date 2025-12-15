# 📺 YouTube Subtitle Downloader

<div align="center">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pakmingc/download-youtube-subtitles/blob/main/download_youtube_subtitles.ipynb)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Colab-F37626?style=for-the-badge&logo=google-colab&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)

**Download YouTube subtitles to text files via Google Colab**

</div>

---

## 🎯 Overview

A simple Python tool to extract and download subtitles from YouTube videos. Supports English and Chinese subtitles with automatic fallback, saving directly to Google Drive.

## ✨ Features

- 📝 **Subtitle Extraction** - Download video captions
- 🌐 **Multi-Language** - English and Chinese support
- 🔄 **Auto-Fallback** - Falls back to Chinese if English unavailable
- ☁️ **Cloud Storage** - Save directly to Google Drive
- 📋 **Preview** - Display subtitles in notebook output

---

## 🚀 Quick Start

1. Click the "Open in Colab" badge above
2. Run all notebook cells
3. Enter YouTube video URL or ID
4. Subtitles saved to Google Drive as `VIDEO_TITLE.txt`

---

## 🛠️ Tech Stack

```
Python 3.x
├── youtube_transcript_api   # Subtitle extraction
├── Google Colab             # Runtime
└── Google Drive             # Storage
```

---

## 📁 Output

| Format | Location |
|--------|----------|
| `.txt` | Google Drive root |

---

## 📫 Contact

📧 pakmingc2@gmail.com

## 📄 License

MIT License
