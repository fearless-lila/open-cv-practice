
# 🏓 Table Tennis Serve analyser (AI-Powered MVP)

A personal project to build an AI-powered tool that detects, analyzes, and classifies table tennis serves using computer vision. This is an MVP (Minimum Viable Product) built in spare time with minimal resources — ideal for enthusiasts, engineers, and sports tech learners.

---

## 🔍 Project Goals

- 🎯 Detect table tennis serve moments from video footage
- 🧠 Build a lightweight ML model to classify serve types (in future phases)
- 🎥 Use computer vision to locate and track the ball during serve motions
- 🧪 Collect data and iterate toward a smarter feedback tool

---

## ✅ MVP Scope

> Focused on **ball motion detection** — no AI model required initially.

- [ ] Video input (match or training clip)
- [ ] Detect small, fast-moving ball using motion + colour filters
- [ ] Visualise and highlight potential serve moments
- [ ] Export data or highlight timestamps for serve events
- [ ] (Future) Classify types of serves with trained ML model

---

## 📁 Folder Structure

```
serve-analyser/
│
├── videos/               # Raw table tennis footage
├── outputs/              # Processed video clips
├── scripts/
│   └── ball_tracker.py   # Motion detection and ball highlighting
├── notebooks/            # (Later) Data exploration & model training
├── README.md             # This file
└── requirements.txt      # Dependencies
```

---

## ▶️ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/fearless-lila/table-tennis-detection.git
cd serve-analyser
```

### 2. Set up environment

```bash
pip install -r requirements.txt
```

### 3. Run the tracker

```bash
python scripts/ball_tracker.py
```

Make sure you have a video file in `videos/` and update the path in the script if needed.

---

## 🛠️ Tech Stack

- `Python 3.10+`
- `OpenCV`
- (Planned) `PyTorch` / `TensorFlow`
- `Streamlit` (for UI in future MVP phase)

---

## 🔮 Future Plans

- Train an AI model to classify serve types (e.g. backspin, sidespin)
- Add UI for users to upload videos and get feedback
- Use pose estimation (like MediaPipe or OpenPose)
- Build a web-based front-end for coaches and players

---

**Note:** This project is for research, learning, and fun — it is not a commercial product.
