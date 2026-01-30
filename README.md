# Real-Time Fall Detection Prototype

Lightweight real-time fall detection prototype built using OpenCV, MediaPipe Pose, and a Random Forest classifier.  
Runs on CPU and demonstrates an early-stage engineering feasibility pipeline for assistive safety monitoring.

This is a research prototype and **not a medical device**.

---

## Project Overview

The system explores whether interpretable biomechanical features derived from pose estimation can support real-time fall detection in a lightweight, privacy-aware pipeline.

Design goals:

- CPU-only real-time operation
- Interpretable feature logic
- Reduced identity exposure using pose landmarks instead of raw video
- Temporal smoothing to reduce false alarms
- Predictable and explainable behavior

The prototype prioritises engineering feasibility and system design over raw performance.

---

## System Pipeline

1. Pose estimation using MediaPipe
2. Feature extraction from body landmarks
3. Temporal smoothing across frames
4. Random Forest classification
5. Real-time alert logic

The architecture is intentionally simple and interpretable to support analysis and future iteration.

---

## Repository Structure


---

## Dataset

The prototype uses a small subset of the public LE2I fall detection dataset for feasibility testing.

- 12 fall videos
- 16 non-fall videos

This dataset is used strictly for engineering experimentation.

---

## Limitations

- Small dataset intended for feasibility exploration
- Not validated for clinical or healthcare deployment
- Prototype only, not a safety-certified system
- Performance metrics are illustrative
- No real patient data used

This project does **not** claim medical effectiveness.

---

## Purpose

The purpose of this repository is to demonstrate early-stage engineering design, real-time pipeline construction, and interpretable machine learning integration in a safety-sensitive context.

It is a technical prototype, not a healthcare product.

---

## Author

Ramandeep Singh  
Independent Computer Vision Engineer  
MSc Advanced Computer Science

GitHub: https://github.com/Ramandeep-AI/ai-fall-detection-prototype
