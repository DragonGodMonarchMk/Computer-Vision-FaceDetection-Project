# Computer-Vision-FaceDetection-Project
# 🧑‍💻 Real-Time Face Detection Project using OpenCV, Haar Cascades & Dlib

This project implements a real-time face detection system using **Haar Cascade Classifiers**, **HOG (Histogram of Oriented Gradients)**, and **Dlib-based 68-Point Facial Landmark Detection**. The solution is optimized for applications requiring accurate face localization, alignment, and key-point tracking from live video feeds.

## 🚀 Project Overview
- Developed real-time face detection using **Haar Cascade Classifiers** for lightweight applications.
- Enhanced facial recognition pipeline with **HOG + Dlib-based landmark detectors** for precise facial feature mapping.
- Built a modular Python pipeline using **OpenCV** to process live video streams from webcams.
- Demonstrated applications of face detection in **emotion detection, AR filters, and biometric identification**.
- Benchmarked detection performance under varying lighting conditions and angles.

## 🛠️ Tech Stack & Tools
- **Python (OpenCV, Dlib, Imutils)**
- **Haar Cascades (OpenCV Pre-trained Models)**
- **HOG (Histogram of Oriented Gradients) Descriptor**
- **68-Point Facial Landmark Detector (Dlib)**
- **Jupyter Notebook (for testing and visualization)**

## 📊 Key Components
| Component                          | Description                                                            |
|-------------------------------------|------------------------------------------------------------------------|
| Haar Cascade Classifier             | Lightweight face detection using Viola-Jones algorithm                 |
| HOG Descriptor + SVM                | Feature descriptor for robust face detection (better than Haar Cascades) |
| Dlib 68-Point Landmark Detection    | High-precision face feature mapping (eyes, nose, lips, jawline)        |
| Real-time Video Processing Pipeline | Capturing live video feed and overlaying detection outputs             |
| Face Alignment & Cropping           | Preprocessing faces for downstream ML applications                    |

## 📈 Results & Performance Insights
- **Haar Cascades**: High-speed detection, suitable for resource-limited environments.
- **HOG + Dlib**: Superior accuracy for landmark detection, slightly heavier computational load.
- Achieved smooth real-time performance (20+ FPS) on standard CPU configurations.
- Robustness tested under different lighting and head pose variations.

## 🧑‍💼 Business Applications
- Security Surveillance (Intrusion Detection, Face Logs)
- Biometric Attendance & Access Control Systems
- Facial Emotion Analysis Tools
- Augmented Reality Face Filters (Snapchat/Instagram-like effects)
- Preprocessing Module for Face Recognition Pipelines

## 👨‍💻 Contributors
- Manish Kumar Das (Project Lead)

## 🏁 How to Run Locally
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run `face_detection_haar.py` for Haar-based detection.
4. Run `face_detection_dlib.py` for Dlib-based landmark detection.
5. Ensure webcam access is enabled.
