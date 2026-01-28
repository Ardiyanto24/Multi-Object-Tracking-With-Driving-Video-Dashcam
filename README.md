# 🚗 Multi-Object Detection & Tracking (Dashcam Video)

End-to-end **Multi-Object Detection and Tracking (MOT)** pipeline for dashcam videos, designed with a **data-centric and failure-aware ML engineering workflow**.  
This project emphasizes **robust preprocessing, EDA-driven modeling decisions, and tracklet-aware evaluation**, suitable for real-world traffic scenes.

---

## 📌 Project Highlights

- 📹 Dashcam-based multi-object detection & tracking
- 🔍 EDA-driven pipeline (not trial-and-error modeling)
- 🧠 Detector-first strategy before full MOT
- 🎯 Focus on **small objects**, **crowded scenes**, and **failure cases**
- 🧱 Modular pipeline: EDA → Preprocessing → Modeling → Evaluation
- 📄 PDF-based insight collectors for reproducibility

---

## 🧠 Problem Statement

Dashcam videos present several challenges for object detection and tracking:

- Heavy **class imbalance** (cars dominate)
- **Small and distant objects**
- **Occlusion & crowded scenes**
- **Motion blur & lighting variation**
- **Track fragmentation** across frames

This project addresses those challenges through **structured EDA, tracklet-aware sampling, and detector stabilization before tracking**.

---
