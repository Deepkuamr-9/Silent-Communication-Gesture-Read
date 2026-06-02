# 🤟 Silent Communication Gesture Read

<div align="center">

### AI-Powered Real-Time Gesture-to-Text Translation System

Transform hand gestures into meaningful text using Artificial Intelligence, Computer Vision, Machine Learning, FastAPI, React, and MediaPipe.

**Python • FastAPI • OpenCV • TensorFlow • MediaPipe • React • TypeScript • Machine Learning**

</div>

---

# 🌟 Overview

**Silent Communication Gesture Read** is an AI-powered gesture recognition platform that translates hand gestures into readable text in real time.

The project combines Computer Vision, Deep Learning, and Modern Web Technologies to bridge communication gaps and create an accessible solution for gesture-based interaction.

Using MediaPipe for hand tracking, TensorFlow for gesture prediction, FastAPI for backend services, and React with TypeScript for the frontend, the system provides a seamless real-time communication experience.

---

# 🎯 Key Features

✅ Real-Time Hand Gesture Recognition

✅ Gesture-to-Text Translation

✅ Live Webcam Processing

✅ Deep Learning-Based Prediction Model

✅ MediaPipe Hand Landmark Detection

✅ FastAPI Backend

✅ React + TypeScript Frontend

✅ WebSocket Support

✅ Modern Responsive UI

✅ Real-Time Communication System

---

# 🏗️ System Architecture

```text
Camera Input
      │
      ▼
MediaPipe Hand Detection
      │
      ▼
Feature Extraction
      │
      ▼
Deep Learning Model
      │
      ▼
Gesture Prediction
      │
      ▼
FastAPI Backend
      │
      ▼
REST API / WebSocket
      │
      ▼
React Frontend
      │
      ▼
Text Output
```

---

# 📂 Project Structure

```text
silent-communication-gesture-read/

├── SignPredictionBackend/
│   ├── gesture_predict_model.h5
│   ├── hand_landmarker.task
│   ├── main.py
│   ├── requirements.txt
│   └── test.ipynb
│
├── web-frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   └── vite.config.ts
│
└── README.md
```

---

# 🛠️ Technology Stack

| Category             | Technology            |
| -------------------- | --------------------- |
| Programming Language | Python 3.11.5+        |
| Backend Framework    | FastAPI               |
| Server               | Uvicorn               |
| Machine Learning     | TensorFlow / Keras    |
| Computer Vision      | OpenCV                |
| Hand Tracking        | MediaPipe             |
| Frontend             | React                 |
| Language             | TypeScript            |
| Communication        | REST API & WebSockets |
| Package Manager      | npm                   |

---

# 🚀 Installation & Setup

## Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/silent-communication-gesture-read.git

cd silent-communication-gesture-read
```

---

## Step 2: Backend Setup

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Start Backend Server

```bash
uvicorn main:app --reload
```

Backend URL:

```text
http://127.0.0.1:8000
```

API Documentation:

```text
http://127.0.0.1:8000/docs
```

---

## Step 3: Frontend Setup

Open a new PowerShell or Terminal window.

Navigate to frontend folder:

```bash
cd web-frontend
```

Install dependencies:

```bash
npm install
```

Start frontend:

```bash
npm run dev
```

Frontend URL:

```text
http://localhost:5173
```

---

# 🧠 How It Works

### Step 1 – Capture Gesture

The webcam captures hand gestures in real time.

### Step 2 – Hand Detection

MediaPipe detects hand landmarks from video frames.

### Step 3 – Feature Extraction

Hand landmark coordinates are extracted and processed.

### Step 4 – Gesture Recognition

The trained Deep Learning model predicts the gesture.

### Step 5 – Text Translation

Recognized gestures are converted into readable text.

### Step 6 – Output Display

The translated text is displayed instantly on the frontend interface.

---

# 📊 Applications

### 🤟 Sign Language Assistance

Supports communication through gesture recognition.

### ♿ Accessibility Solutions

Helps individuals with hearing or speech impairments.

### 🎓 Educational Platforms

Useful for learning and understanding sign language.

### 🏥 Healthcare Communication

Assists communication in healthcare environments.

### 🤖 Human-Computer Interaction

Enables touchless digital interaction systems.

---

# 📈 Skills Demonstrated

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Computer Vision
* MediaPipe
* OpenCV
* FastAPI
* React
* TypeScript
* REST APIs
* WebSockets
* Full Stack Development

---

# 🔮 Future Enhancements

* Voice Output from Predicted Text
* Multi-Language Translation
* Mobile Application Support
* Advanced Deep Learning Models
* Cloud Deployment
* Expanded Gesture Vocabulary
* Offline Recognition Mode

---

# 👨‍💻 Project Creator

## Deep Kumar

Computer Science Graduate

Passionate about Artificial Intelligence, Machine Learning, Computer Vision, Data Science, and Full-Stack Development.

---

# 🤝 Contributor

## Rimpa Das

Contributed to the successful completion, testing, and development of the project.

Special thanks for the valuable support and collaboration throughout the project development process.

---

# 🙏 Acknowledgements

This project was successfully developed through the combined efforts of:

### Deep Kumar

**Project Creator & Lead Developer**

### Rimpa Das

**Project Contributor & Collaborator**

Their dedication and teamwork helped bring this AI-powered communication platform to life.

---

# ⚠️ Disclaimer

This project is developed for educational and research purposes.

Recognition accuracy may vary depending on lighting conditions, camera quality, gesture visibility, and model performance.

---

# ⭐ Support

If you found this project useful:

⭐ Star the Repository

🍴 Fork the Repository

🚀 Share it with others

---

<div align="center">

## 🤟 Silent Communication Gesture Read

### Bridging Communication Through Artificial Intelligence

**Built with ❤️ by Deep Kumar**

**Special Contribution by Rimpa Das**

</div>
