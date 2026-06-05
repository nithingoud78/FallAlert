# Fall Detection System

An AI-powered real-time fall detection and emergency alert system built using ESP32, MPU6050, GPS, TensorFlow Lite, Node.js, MongoDB, and React.

The system continuously monitors motion data, detects fall events using machine learning, and instantly sends alerts along with location information to a cloud-connected monitoring dashboard.

---

## Features

* Real-time fall detection
* ESP32-based edge processing
* MPU6050 motion sensing
* GPS location tracking
* TensorFlow Lite model deployment
* Cloud-connected backend
* MongoDB data storage
* React monitoring dashboard
* Historical event tracking
* Live alert notifications

---

## Technology Stack

### Hardware

* ESP32
* MPU6050
* GPS Module

### Machine Learning

* Python
* TensorFlow
* TensorFlow Lite
* Scikit-learn

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.IO

### Frontend

* React
* Axios
* Socket.IO Client

---

## Project Structure

```text
backend/
frontend/
esp32/
machine-learning/
docs/

README.md
LICENSE
CONTRIBUTING.md
CHANGELOG.md
.gitignore
```

---

## Hardware Setup

| Component  | Purpose           |
| ---------- | ----------------- |
| ESP32      | Main Controller   |
| MPU6050    | Motion Detection  |
| GPS Module | Location Tracking |

---

## Installation

### Backend

```bash
cd backend
npm install
npm start
```

### Frontend

```bash
cd frontend
npm install
npm start
```

### ESP32

1. Open Arduino IDE
2. Install ESP32 Board Package
3. Install required libraries
4. Upload firmware to ESP32

---

## Machine Learning Workflow

Dataset Collection

↓

Data Preprocessing

↓

Model Training

↓

TensorFlow Lite Conversion

↓

ESP32 Deployment

↓

Real-Time Inference

---

## Future Improvements

* SMS Alerts
* WhatsApp Notifications
* Mobile Application
* Battery Monitoring
* Multi-device Support
* Advanced Activity Recognition

---

## License

This project is licensed under the MIT License.

---

## Author

Nithin Goud

Bachelor of Engineering

Embedded Systems | IoT | Machine Learning
