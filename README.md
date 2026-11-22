# quest-map-speedup
Standalone Beat Saber custom map speed-up and slow-down generator for Meta Quest using Termux, Python, and ffmpeg—creates pitch-preserved 1.15x/1.25x copies straight in SongCore without a PC.
# Quest Beat Saber Map Speed-Up Generator (`speedup.py`)

Create standalone **1.15x, 1.25x, or custom speed** copies of any custom Beat Saber map directly on your Meta Quest headset using **Termux**, **Python**, and **`ffmpeg`**—no PC required.

## Prerequisites
* **Beat Saber** modded with **SongCore**
* **Termux** + **Hacker's Keyboard** (enabled in Android Language & Input settings so **Enter** works)
* **Python**, **`wheel` / `setuptools`**, and **`ffmpeg`** installed in Termux

## Setup & Run
1. Install Python, `ffmpeg`, and Python build tools (`setuptools` and `wheel`) in Termux:
   ```bash
   termux-setup-storage
   pkg update -y && pkg install -y python ffmpeg
   pip install --upgrade pip setuptools wheel
2. Download speedup.py into /sdcard/Download and run:bash
python /sdcard/Download/speedup.py

3. Search for a song name, pick its number, and enter a speed multiplier (e.g. 1.25 for faster or 0.85 for slower). The new map appears automatically in your Custom Levels tab!
