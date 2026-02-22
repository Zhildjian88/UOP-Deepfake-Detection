# UOP-Deepfake-Detection

A robust deepfake video detection system built to combat KYC fraud, online scams, and misinformation. This project leverages distributed computing and state-of-the-art architectures to ensure high-fidelity detection across multiple large-scale datasets.

## 📺 Project Demo
Click the link below to view the inference pipeline in action:
**[View Flask Inference Deepfake Detection Demo](https://www.dropbox.com/scl/fi/sunsw6tld7iqencc02ekg/Flask_Inference_Deepfake_Detection.mp4?rlkey=bakc59to48gm77e2rb5z6ndvr&st=kwor0vg3&dl=1)**

---

## 📊 Slides (Architecture & Results)

A concise slide deck summarising the system design, model architecture,
and evaluation results for this project:

👉 **View slides (PDF):** `slides/Deepfake_Detection_Public_Summary.pdf`

---

## 🚀 Key Features
* **Distributed Processing:** Utilizes **Apache Spark** for handling large-scale video datasets and preprocessing.
* **Comprehensive Training:** Robust model trained on **FaceForensics++**, **Celeb-DF**, and **DFDC**.
* **Real-time Inference:** A Flask-based web application for easy video uploading and fraud detection.
* **Optimized Architecture:** Fine-tuned EfficientNet backbone with an optimal unfreeze of ~60 layers for maximum accuracy.

## 🛠️ Tech Stack
* **Language:** Python
* **Web Framework:** Flask
* **Distributed Computing:** Apache Spark
* **Deep Learning:** PyTorch / TensorFlow (EfficientNet)
* **Datasets:** FaceForensics++, Celeb-DF, DFDC

## 📁 Repository Structure
* `/app`: Flask application and inference scripts.
* `/models`: Model architecture and weight files.
* `/data`: Preprocessing scripts for Spark-based data handling.
* `/notebooks`: Development logs and training evaluations.

---
