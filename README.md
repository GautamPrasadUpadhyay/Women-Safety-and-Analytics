🚨 Women Safety & Analytics — AI-Powered Protection System

A smart, AI-driven safety platform built using MERN Stack, Flask ML backend, OpenCV, and YOLO detection models.
The system enables instant SOS alerts, real-time location tracking, and automatic threat detection to protect women during emergencies.

⭐ Key Features
🆘 Emergency SOS Button

Women can press the SOS button during danger.

Instantly sends alert signals to:

🚓 Nearest Police Station

👨‍👩‍👧 Parents / Emergency Contacts


Includes live GPS location, user details, and threat status.

🎥 AI Threat Detection (OpenCV + YOLO)

Uses YOLO for real-time person, weapon, and suspicious activity detection.

OpenCV processes live video frames from the user’s camera.

Automatically triggers alerts if threats are detected.


📍 Live Location Tracking

Tracks user location continuously until they are safe.

Route mapping using Google Maps API.

📊 Safety Analytics Dashboard

Displays:

Crime heatmaps

Hotspot detection using K-Means

Time-based safety trends

Risk score predictions

📝 Incident Reporting

File reports with images, location, and descriptions.

All data stored securely in MongoDB.

🤖 Machine Learning Components

YOLOv5/YOLOv8 — Object & threat detection

OpenCV — Live camera analysis & frame processing

Random Forest / Logistic Regression — Location safety scoring

K-Means — Hotspot clustering

Naive Bayes / SVM — Incident classification (text-based)

Flask Server — Runs all ML models and exposes REST APIs to MERN backend

🧠 Tech Stack
Frontend

React.js

TailwindCSS / Material UI

Google Maps Platform

Backend

Node.js + Express (MERN Backend)

Flask (Python ML Server)

Database

MongoDB (User, Reports, Alerts, Analytics)

ML Libraries

Python

OpenCV

YOLO

Scikit-learn

NumPy, Pandas

🔧 How It Works
User Presses SOS
      ↓
Location + Video Feed Captured
      ↓
MERN Backend → Sends data to Flask ML Server
      ↓
YOLO + OpenCV Detect Threats
      ↓
Risk Score Computed (ML Models)
      ↓
Alerts Sent to Police + Parents
      ↓
Dashboard Updates with Analytics

🚀 Getting Started
Clone the repository:
git clone <repo-url>
cd women-safety-analytics

Install MERN dependencies:
npm install

Install ML backend dependencies:
pip install -r requirements.txt

Start servers:
npm start          # MERN frontend + backend
python app.py      # Flask ML server
