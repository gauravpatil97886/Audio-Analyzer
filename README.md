# 🎧 AudioLens – Audio Analysis Report Tool

**AudioLens** is a modern, browser-based audio analysis tool that lets you upload audio files or provide audio URLs and instantly get a **professional, detailed audio quality report**.

It runs fully on the client using **Web Audio APIs**, requires **no backend**, and works directly in your browser.

🔗 **Live Demo:** [https://gauravpatil97886.github.io/Audio-Analyzer/](https://gauravpatil97886.github.io/Audio-Analyzer/)
<img width="1917" height="961" alt="image" src="https://github.com/user-attachments/assets/55dd2fc1-290c-4c1c-9f44-6dcc54d4a077" />

---

## ✨ Why AudioLens?

AudioLens is built for:

* Developers validating audio quality
* QA teams checking call recordings
* Content creators verifying audio specs
* Anyone who wants quick, reliable audio insights

**Upload → Analyze → Export Report** — that simple.

---

## 🚀 Key Features

### 🎵 Audio Analysis

* File name & format detection (MP3, WAV, M4A, AAC)
* Duration (mm:ss + seconds)
* Sample rate (kHz)
* Bitrate (kbps)
* Channel detection (Mono / Stereo)
* File size
* Loudness calculation (dBFS)
* Automatic **quality grading** (Excellent / Good / Average / Poor)

### 📁 Flexible Input Options

* Upload single or multiple audio files
* Drag & drop support
* Analyze audio directly from **public URLs**
* Batch processing for multiple files

### 🎚️ Advanced Audio Player

* Built-in audio player
* Stereo / Left / Right channel isolation
* Interactive waveform visualization
* Live audio visualizer
* Seek, volume, and mute controls

### 📊 Batch Analysis

* Analyze multiple files or URLs at once
* Individual quality status per file
* Clear batch summary view

### 📄 Export & Sharing

* Copy analysis report to clipboard
* Download report as HTML
* Export **print-ready PDF** (via browser print)
* Share summary using Web Share API

### 🌙 User Experience

* Light & dark mode
* Smooth animations
* Responsive design (mobile + desktop)
* Local analysis history (stored in browser)

---

## 🧠 How It Works

AudioLens uses modern browser APIs:

* **Web Audio API** for decoding and analysis
* **AudioContext** for waveform & loudness calculation
* **LocalStorage** for history persistence

All processing happens **locally in your browser** — no uploads to any server.

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (modern UI, animations)
* Vanilla JavaScript
* Web Audio API
* LocalStorage

No frameworks. No backend. No dependencies.

---

## 📦 Supported Formats

* MP3
* WAV
* M4A
* AAC

(Max file size: **50 MB**)

---

## 🖥️ Running Locally

```bash
# Clone the repository
git clone https://github.com/gauravpatil97886/Audio-Analyzer.git

# Open index.html in your browser
```

That’s it — no build step required.

---

## 📸 Screenshots

> Add screenshots here for better GitHub visibility

* Upload screen
* Analysis results
  <img width="1917" height="961" alt="image" src="https://github.com/user-attachments/assets/ae34759a-298a-4caf-9f0b-11cfba8f9d90" />
* Audio player & waveform
* Batch analysis

---

## 🔒 Privacy

✔ No server uploads
✔ No tracking
✔ No data collection
✔ All processing stays on your device

---

## 🧩 Limitations

* URL analysis depends on **CORS support** from the source
* Loudness is estimated using RMS (browser-level, not studio LUFS)
* PDF export uses browser print dialog

---

## 🛣️ Future Improvements

* LUFS-based loudness measurement
* Noise floor & silence detection
* Frequency spectrum analysis
* API version (backend-powered)
* Call-center focused presets

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## ⭐ Support

If you find this project useful:

* Star the repository ⭐
* Share it with others
* Give feedback or ideas

---

## 👨‍💻 Author

**Gaurav Patil**
Backend Engineer | Product-focused Developer

Built with ❤️ and attention to detail.

---

## 📜 License

MIT License — feel free to use, modify, and distribute.
