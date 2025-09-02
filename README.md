# 🎵 YouTube to MP3 Trimmer (Google Colab Script)

This project provides a simple **Google Colab script** to:  
1. Download audio from YouTube videos as **MP3**.  
2. Trim any selected portion of the audio (start–end seconds).  
3. Export and download the trimmed clip to your system.  

It’s perfect for:  
- Music-based games (e.g., *Guess the Song* 🎶).  
- Creating short ringtones or background clips.  
- Extracting highlights from long songs or speeches.  

---

## 🚀 Features
- Download YouTube audio in **MP3 format** (via [`yt-dlp`](https://github.com/yt-dlp/yt-dlp)).  
- Trim audio between **custom start and end times**.  
- Export with a **custom filename**.  
- Works seamlessly in **Google Colab** (no local setup needed).  

---

## 📋 Requirements
The script installs these dependencies automatically in Colab:
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) → download YouTube videos.  
- [pydub](https://github.com/jiaaro/pydub) → process audio.  
- [ffmpeg](https://ffmpeg.org) → audio conversion backend.  

---

## 🛠️ Usage

1. Open the notebook in **Google Colab**.  
2. Run the first cell to install dependencies.  
3. Paste your YouTube URL in the `url` variable.  
4. Set your `start_time` and `end_time` in seconds.  
5. Run the script.  
6. Download the trimmed MP3 clip.  

---

## 💻 Example

```python
url = "https://www.youtube.com/watch?v=4wrfB5aH8Ms"

# Set trimming window (in seconds)
start_time = 65   # start at 1:05
end_time   = 81   # end at 1:21

# Output file name
output_file = "abc.mp3"
```

✅ This will:  
- Download the YouTube audio,  
- Trim the portion from **1:05 → 1:21**,  
- Save and download as `abc.mp3`.  

---

## 📂 Output
- The trimmed MP3 will be saved in Colab as `abc.mp3`.  
- It will then be downloaded automatically to your device.  

---

## ⚠️ Disclaimer
This project is intended for **educational and personal use only**.  
Please respect **copyright laws** when downloading or sharing content.  

---

## 🏷️ Tags
`youtube` `yt-dlp` `mp3` `audio-processing` `colab` `python` `pydub` `ffmpeg` `song-trimmer`
