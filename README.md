# 🧠 FOCUS AI — Teacher Assistant System

FOCUS AI is an AI-powered, browser-based system designed to help teachers monitor student attention in real time.

It analyzes body posture and facial orientation to estimate focus levels, providing useful insights to improve classroom engagement.

> ⚡ Runs completely in the browser — no server or backend required.

---

## 🚀 Features

### 🎥 Real-Time Attention Detection

* Multi-person detection using MoveNet
* Head orientation & posture tracking
* Nose deviation-based focus scoring
* Adjustable strictness control
* Smooth real-time processing
* FPS monitor for performance

---

### 📊 AI Dashboard

* Live student count
* Focus percentage tracking
* Color-coded attention status
* Auto-updating logs

---

### 🎥 Recording & Export

* Record sessions using MediaRecorder
* Save recordings (WebM → MP4 supported)
* Export data as CSV or JSON

---

### 📚 Student Database

* Add and manage students
* Store student images locally
* Data saved using IndexedDB
* Clean card-based UI

---

### 🌗 UI & Experience

* Light/Dark mode toggle
* Responsive design (TailwindCSS)
* Smooth animations & transitions
* Sidebar navigation system

---

## 🧠 Tech Stack

**AI & Processing**

* TensorFlow.js
* MoveNet (MultiPose)
* Custom attention detection logic
* Kalman tracking

**Frontend**

* HTML, CSS (TailwindCSS)
* JavaScript
* Canvas + Video Processing

**Storage**

* IndexedDB (local database)

---

## 📁 Project Structure

```
/
├── index.html        # Home page
├── run.html          # AI dashboard
├── students.html     # Student database
├── Web.html          # Experimental version
├── assets/           # Images & sounds
└── README.md
```

---

## ⚙️ How to Run

1. Download or clone the repository
2. Open the project folder
3. Run:

```
index.html
```

👉 Make sure to allow camera access in your browser.

---

## 📌 Requirements

* Modern browser (Chrome recommended)
* Camera-enabled device
* JavaScript enabled

---

## 🎯 Future Improvements

* Face recognition system
* Automatic student identification
* Attention heatmaps
* Teacher login system
* Cloud sync & analytics dashboard

---

## 💡 Purpose

This project aims to assist teachers by providing real-time insights into student engagement using AI, helping improve learning efficiency in classrooms.
