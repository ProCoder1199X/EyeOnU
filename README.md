# 👁️ EyesOnU v1

**EyesOnU** is an open-source, AI-powered focus detector that keeps you *literally* in check.  
Using your webcam, it monitors whether you’re paying attention — and if you’re distracted for more than a set time (default 3 seconds), it plays **full-screen GIF “reactions”** to snap you back.

---

## ✨ Features (v1)
- **Real-time focus detection** using OpenCV’s face + eye tracking
- **Custom GIF reactions** (AK-47, explosions, cat slaps… your imagination is the limit)
- **Sequential playback** — cycle through your reaction list
- **Fullscreen immersive playback** (10 seconds per reaction)
- **Customizable delay** before reaction triggers (default: 3s)
- **Session control UI** — start, stop, select camera, pick GIFs
- **Futuristic Qt-based interface** with real-time camera preview
- **Cross-platform** (Windows, Mac, Linux — as long as OpenCV + PyQt5 work)

---

## 📦 Installation
```bash
# Clone the repo
git clone https://github.com/<your-username>/EyesOnU.git
cd EyesOnU

# Create virtual environment (optional but recommended)
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
