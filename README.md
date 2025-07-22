# 📺 YouTube Video Size Analyzer

A Python tool to fetch all videos from a YouTube channel and estimate their file sizes (in MB) using the YouTube Data API and `yt_dlp`, without downloading the videos.

---

## 🚀 Features

- Uses **YouTube Data API v3** to get all uploaded video IDs.
- Uses **`yt_dlp`** to fetch video metadata and approximate file size.
- Calculates:
  - Individual video sizes
  - Total size of all valid videos
  - Number of successfully analyzed videos
- Handles errors gracefully.
- Clean command-line output with running totals.

---

## 🛠️ Technologies Used

- Python 3
- [google-api-python-client](https://pypi.org/project/google-api-python-client/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)

---

## 📦 Installation

```bash
pip install google-api-python-client yt-dlp
