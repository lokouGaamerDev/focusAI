FOCUS AI — Student Attention Detection System

FOCUS AI is a browser-based real-time attention monitoring system designed for classrooms.
It leverages TensorFlow.js, MoveNet, Face Mesh, Kalman tracking, IndexedDB, and a fully responsive TailwindCSS interface.

This project runs entirely locally in the user's browser—no server, no backend.

📌 Features
🎥 Real-Time Attention Detection

(from run.html 

Run

)

Multi-person detection using MoveNet

Head orientation and shoulder-center alignment

Nose deviation–based focus scoring

Strictness-based sensitivity control

AI processing pipeline with requestAnimationFrame loop

FPS monitor for performance feedback

Fully responsive video-canvas rendering

📊 AI Metrics Dashboard

Student Count

Focus Percentage

Dynamic color-coded focus status

HUD-style top display

Auto-updating attention log

🎥 Recording & Exporting

Canvas recording using MediaRecorder API

Save recordings as WebM

Convert WebM → MP4 (via FFmpeg WASM)

Export attention data as:

CSV

JSON

🧭 Navigation System

Hamburger menu drawer

Links to:

Student Database

Trainer (placeholder)

Version display
(from run.html drawer system)

🌗 Theme System

Light/Dark toggle

Smooth transitions

Remembers last selected theme using localStorage
(from index.html, run.html, students.html


home

 

Run

 

students

)

📚 Students Database

(from students.html 

students

)

A built-in offline student management system powered by IndexedDB:

Features

Add new students

Upload & store student photos (Base64)

Persistent data (saved locally in the browser)

Student card grid UI

Delete students

Glassmorphism UI

No server or external database required.

🏠 Home Page

(from index.html 

home

)

Includes:

Animated neon gradient title

Logo intro effect

Launch button

Theme toggle

Smooth fade-in animation

🧠 Technology Stack
AI & Processing

TensorFlow.js

MoveNet (Multipose)

Custom attention classifier logic

Kalman prediction for tracking stabilization

Pose landmark extraction

Real-time canvas rendering

Frontend

TailwindCSS

Glassmorphism

Animated intro screen

Drawer navigation

Canvas + video overlay UI

Custom sound effects (buttons & sliders)

Storage

Browser-native IndexedDB

Persistent student records

📁 Project Structure
/
├── index.html          # Home page
├── run.html            # Main AI tracking dashboard
├── students.html       # Student database
├── Web.html            # Older experimental AI version
├── ailogo.png          # Branding logo
├── click.wav           # UI sound
├── slider.wav          # UI sound
└── README.md

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/yourusername/focus-ai.git
cd focus-ai

2. Run the App

Just open index.html in any modern browser:

Chrome recommended

Ensure “Allow Camera Access” is enabled

No backend needed.

📌 Requirements

Chrome / Firefox (latest versions)

Device with camera

JavaScript enabled

🛠 Future Enhancements

Face recognition using embeddings

Automatic student identification

Class/session reporting dashboard

Heatmap of attention

Cloud sync (optional)

Teacher login

Model training UI
