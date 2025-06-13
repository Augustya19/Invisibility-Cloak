# CloakX: Real-Time Invisibility Cloak 🔮

A computer vision project that simulates real-life invisibility using **Python** and **OpenCV**. Inspired by the Harry Potter-style cloak, this system uses background segmentation to detect and remove objects (like a red cloak) from live video, replacing them with the background in real-time.

---

## 🧠 How It Works

1. **Capture the Background Frame** – The system captures a few seconds of the static background before the object enters.
2. **Color Detection & Masking** – It detects a specific color (e.g., red) in each frame of the video.
3. **Image Segmentation** – The selected color area is segmented and replaced with the pre-captured background.
4. **Result** – The cloak (or object) appears invisible to the viewer.

---

## 🎯 Features

- Real-time invisibility effect via webcam
- Accurate color masking and segmentation
- Background replacement using NumPy + OpenCV
- Easy-to-extend for any solid-colored object

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **NumPy**

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- OpenCV
- NumPy

### Installation

git clone https://github.com/Augustya19/Invisibility-Cloak.git
cd Invisibility-Cloak
pip install opencv-python numpy

### Running the script 
python cloak.py

### 📌 Tips for Best Results

Use a brightly colored cloth (preferably red, blue, or green).
Ensure consistent lighting.
Avoid wearing clothes similar in color to the cloak.
Keep the background as static as possible.

### 💡 Potential Use Cases

Augmented Reality filters
Video production effects
Magic tricks & entertainment
Education on image processing


