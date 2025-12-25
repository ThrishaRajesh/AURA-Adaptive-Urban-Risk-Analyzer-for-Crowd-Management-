# AURA – Adaptive Urban Risk Analyzer for Crowd Management

AURA is an AI-driven crowd safety and risk prediction platform designed to prevent
stampedes and high-risk crowd incidents using real-time video analytics,
adaptive risk modeling, and intelligent routing.

Unlike traditional CCTV monitoring, AURA proactively predicts dangerous crowd
conditions and delivers actionable insights to both authorities and citizens.

---

## Key Capabilities

- Real-time crowd density and movement analysis
- Adaptive Risk Scoring Engine (AURA-Core)
- Crowd Pressure Index (CPI) & Exit Load Balance Score (ELBS)
- Surge, panic, and huddle detection
- Dynamic safe-route generation (safety-first routing)
- Multi-zone admin command dashboard
- Citizen-facing mobile safety application

---

## System Architecture

- **Backend Intelligence Engine** – Risk computation & decision logic
- **Video & Data Processing Layer** – Crowd metrics extraction & simulation
- **Admin Dashboard (Web)** – Visualization, alerts, analytics
- **Mobile App (Flutter)** – Public safety guidance & SOS features

---

## Module Breakdown

### 1️⃣ Backend – Risk Intelligence & Algorithms
- Adaptive Risk Scoring (AURA-Core)
- Crowd Pressure Index (CPI)
- Exit Load Balance Score (ELBS)
- Surge & huddle detection
- Pressure zone classification
- Dynamic safe-route computation

**Tech:** Python 3, OpenCV, NumPy, Pandas, Analytics Algorithms

---

### 2️⃣ Video Processing & Simulation
- Video-based crowd density extraction
- Optical flow based motion analysis
- Scenario simulation for testing
- JSON-based data streaming to backend

**Input:** Sample YouTube crowd video  
**Output:** Structured crowd metrics (`.json`)

**Tech:** Farneback Optical Flow, Contour Detection, Risk Scoring Engine

---

### 3️⃣ Admin Dashboard (Web)
- Multi-zone command center
- Live heatmaps & alerts
- CPI, ELBS, and risk timelines
- Simulation control & analytics view

**Tech:** React.js, Tailwind CSS, React-Toastify, Leaflet.js, Node.js + Express.js, Twilio 

---

### 4️⃣ Mobile App (Flutter)
- Live zone safety status
- Dynamic safe-route navigation
- Emergency alerts & SOS
- Lightweight citizen interface

**Tech:** Flutter, Dart, Android Studio 

---

## Repository Structure


---

## How to Run (Local Setup)


