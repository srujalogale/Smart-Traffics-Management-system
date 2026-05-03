# 🚦 AI-Based Predictive Smart Traffic Management System

An intelligent traffic management system that uses **Computer Vision and Machine Learning** to monitor traffic, predict congestion, and dynamically control traffic signals in real-time.

This is a unified repository containing both the AI-powered backend and the React-based frontend for the Smart Traffic Management System.

---

## 📌 Overview

This project addresses the limitations of traditional fixed-timing traffic signals by introducing a **software-based smart system** that:

- Detects vehicles using **YOLO (Computer Vision)**
- Estimates traffic density in real-time
- Predicts future congestion using **Machine Learning**
- Dynamically adjusts signal timings
- Supports **emergency vehicle prioritization**

---

## 🏗️ Project Structure
- **/frontend**: React (Vite + TS) dashboard for real-time monitoring and administration.
- **/backend**: Flask (Python) server handling YOLOv8 vehicle detection and dynamic signal scheduling.

---

## 🎯 Key Features

- 🔍 **Real-Time Vehicle Detection** using YOLOv8
- 📊 **Lane-wise Traffic Density Analysis**
- 🧠 **Predictive Model (Random Forest)** for traffic forecasting
- 🚦 **Dynamic Signal Control Algorithm**
- 🚑 **Emergency Vehicle Priority (Green Corridor)**
- 🖥️ **Live Monitoring Dashboard**
- 📈 **Traffic Analytics & Visualization**
- 🎥 **Multi-Lane Simulation (Webcam + Synthetic Inputs)**

---

## ⚙️ Tech Stack

### 🔹 Backend
- Python
- Flask (API)
- OpenCV
- YOLOv8 (Ultralytics)
- Scikit-learn

### 🔹 Frontend
- HTML / CSS / JavaScript
- React (Vite + TS)

### 🔹 Machine Learning
- Random Forest Regression

---

## 🚀 Quick Start & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/srujalogale/Smart-Traffics-Management-system-.git
cd Smart-Traffics-Management-system-
```

### 2️⃣ Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
# venv\Scripts\activate    # (Windows)
pip install -r requirements.txt
python app.py
```
The backend server will run on `http://localhost:5000`.

### 3️⃣ Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```
The dashboard will run on the port specified by Vite.

---

Developed for modern urban traffic optimization.
© 2026 Smart Traffic Management System
