# 💊 YOLO11 Pill Detection, Tracking & Color Classification

A real-time computer vision system for **pharmaceutical capsule detection, multi-object tracking, and automated color classification** using **YOLO11, ByteTrack, and HSV color analysis**.

---

## 🎯 Highlights

- ✅ 99.42% mAP@0.5
- ✅ 94.61% mAP@0.5:0.95
- ✅ Real-time Multi-Object Tracking
- ✅ HSV-based Capsule Color Classification
- ✅ Industrial Quality Inspection Pipeline

---

# 📸 Results

### Detection

![Detection](https://github.com/user-attachments/assets/5aafd495-b4d9-4b0b-b33f-0042006d3581)

---

### Tracking

![Tracking](https://github.com/user-attachments/assets/2740ed9e-c1e0-42f4-90db-25fc388a3552)

---

### Training Performance

![Metrics](https://github.com/user-attachments/assets/023e7529-1ab5-4592-8803-f4966da63a93)

---

# 📖 Overview

This project presents an automated computer vision pipeline for pharmaceutical capsule inspection. Capsules moving on a conveyor belt are detected using **YOLO11**, tracked across consecutive frames using **ByteTrack**, and classified according to their color using **HSV color analysis**.

The system enables accurate and real-time quality control suitable for industrial production lines.

---

# 🚀 Features

- Real-time capsule detection
- Multi-object tracking
- Unique ID assignment
- HSV color classification
- Confidence score visualization
- Bounding box visualization
- White–Blue capsule detection
- White–Red/Pink capsule detection

---

# ⚙️ Pipeline

```text
Input Video
      │
      ▼
YOLO11 Detection
      │
      ▼
ByteTrack Tracking
      │
      ▼
Capsule Cropping
      │
      ▼
HSV Color Analysis
      │
      ▼
Final Output
(Bounding Boxes + IDs + Colors)
