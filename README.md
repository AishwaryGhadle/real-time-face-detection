# 🎥 Real-Time Face Detection using OpenCV

## 📌 Overview

This project implements a real-time face detection system using OpenCV and a webcam. It detects human faces instantly from live video streams, making it suitable for surveillance and basic cyber security applications.

---

## ❗ Problem Statement

To build a real-time application that detects human faces using a webcam without requiring a dataset.

---

## ⚙️ Methodology

### 1. Video Capture

* Captured live video using webcam
* Frame-by-frame processing

### 2. Face Detection Model

* Haar Cascade Classifier (OpenCV)
* Pre-trained model for face detection

### 3. Detection Process

* Convert frames to grayscale
* Detect faces using classifier
* Draw bounding boxes around detected faces

---

## 📈 Results

* Successfully detects faces in real-time
* Works efficiently under normal lighting conditions
* Low latency detection using OpenCV

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/real-time-face-detection.git
cd real-time-face-detection
pip install -r requirements.txt
python face_detection.py
```

---

## 📁 Project Structure

```bash
real-time-face-detection/
│
├── face_detection.ipynb
├── README.md
├── requirements.txt
```

---

## 📌 Future Improvements

* Add face recognition (identify person)
* Improve detection in low light
* Integrate with security systems

---

## 📜 License

MIT License

---

## 👤 Author

**Aishwary Ghadle**

