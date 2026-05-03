# SonicFlow-A-PyQt6-Audio-Player-with-Playback-Speed-Control

SonicFlow is a desktop audio player built using Python and PyQt6. It allows users to play audio files from their system, control playback, and adjust playback speed through a simple graphical interface.

This project was created to explore GUI development and multimedia handling in Python using PyQt6.

---
## Screenshots
<img width="1919" height="1005" alt="Image" src="https://github.com/user-attachments/assets/563673ab-44ec-4a49-b06e-ec93c3861cf2" />

<img width="1918" height="1005" alt="Image" src="https://github.com/user-attachments/assets/839ce8a8-4f38-4d93-b849-179e6ae61ada" />

<img width="1919" height="1008" alt="Image" src="https://github.com/user-attachments/assets/659fba29-dcbe-4776-958d-e21e1aa89581" />

---

## 🚀 What This Project Does

SonicFlow provides a basic but functional audio player with the following capabilities:

* Load audio files from a folder or select a single file
* Display available audio files in a list
* Play selected audio
* Pause and resume playback
* Reset and restart audio from the beginning
* Adjust playback speed (0.5x to 2.0x)

The application is designed to be simple, responsive, and easy to use.

---

## 🧩 How It Works (Core Components)

### 🎵 QMediaPlayer

Handles audio playback. It is responsible for:

* Loading audio files
* Playing, pausing, and stopping audio
* Controlling playback position and speed

### 🔊 QAudioOutput

Manages audio output (sound). It connects with `QMediaPlayer` to actually produce sound.

### 🖥️ PyQt6 Widgets

Used to build the interface:

* `QPushButton` → controls (play, pause, resume, reset)
* `QListWidget` → displays audio files
* `QSlider` → controls playback speed
* `QLabel` → shows title and status messages

### 📁 File Handling (os module)

* Reads files from selected folders
* Filters `.mp3` files
* Dynamically updates the file list

---

## ✨ Features

* ▶️ Play, Pause, Resume, Reset controls
* ⚡ Playback speed control using slider
* 📁 Folder selection to load multiple audio files
* 🎧 Single file selection option
* 🧭 Clean and minimal user interface

---

## 🛠️ Tech Stack

* **Python**
* **PyQt6** (GUI Framework)
* **QMediaPlayer & QAudioOutput** (Audio handling)
* **os module** (File system interaction)

---

## ▶️ How to Use

1. Click **"Choose File"**
2. Select a folder or a single audio file
3. Pick a file from the list
4. Click **Play**
5. Use:

   * **Pause** → temporarily stop audio
   * **Resume** → continue playback
   * **Reset** → restart audio from beginning
6. Adjust the **slider** to change playback speed
---

## 🚧 Future Improvements

* Add volume control slider
* Add audio progress bar (timeline)
* Support more formats (.wav, .flac)
* Improve UI design and themes
* Add playlist functionality

---

## 🧠 What I Learned

* Building GUI applications using PyQt6
* Handling multimedia playback in Python
* Managing user input and UI events
* Structuring a complete desktop application

---

## 👤 Author

**Rajveer Singh Tanwar**

---

⭐ If you found this project useful, consider giving it a star!

