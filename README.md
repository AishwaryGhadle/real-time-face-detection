# 🎥 Real-Time Face Detection using OpenCV

## 📌 Overview

This project implements a real-time face detection system using OpenCV and a webcam. It detects human faces instantly from live video streams.

---

## ❗ Problem Statement

To build a real-time application that detects human faces using a webcam without requiring a dataset.

---

## ⚙️ Methodology

### Video Capture

* Captured live video using webcam
* Frame-by-frame processing

### Face Detection Model

* Haar Cascade Classifier (OpenCV)
* Pre-trained model

### Detection Process

* Convert frames to grayscale
* Detect faces
* Draw bounding boxes

---

## 📈 Results

* Real-time face detection achieved
* Works efficiently under normal lighting
* Low latency performance

### 📊 Output

![Face Detection](face_output.png)

---

## 🚀 How to Run

```bash
git clone https://github.com/AishwaryGhadle/real-time-face-detection.git
cd real-time-face-detection
pip install -r requirements.txt
jupyter notebook
```

Open:

```bash
face_detection.ipynb
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

* Face recognition (identify individuals)
* Improve low-light detection
* Integrate with security systems

---

## 📜 License

MIT License

---

## 👤 Author

**Aishwary Ghadle**


