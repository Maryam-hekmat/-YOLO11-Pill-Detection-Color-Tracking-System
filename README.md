# 💊 YOLO11 Pill Detection, Tracking & Color Classification

A real-time computer vision system for **pharmaceutical capsule detection, multi-object tracking, and color classification** using **YOLO11, ByteTrack, and HSV color analysis**.

**🎯 Highlights**

* ✅ 99.42% mAP@0.5
* ✅ Real-time multi-object tracking
* ✅ Automated capsule color classification
* ✅ End-to-end quality control pipeline for pharmaceutical production

---

# 📖 Project Overview

This project presents an end-to-end computer vision pipeline for **automated pharmaceutical quality inspection**. The system detects capsules moving on a conveyor belt, assigns a unique tracking ID to each capsule, and classifies its color in real time.

The workflow combines modern deep learning with classical computer vision techniques to achieve accurate and efficient inspection suitable for industrial environments.

---

# 🚀 Features

* Real-time capsule detection using **YOLO11n**
* Multi-object tracking with **ByteTrack**
* HSV-based color classification
* Stable object IDs across video frames
* Bounding box visualization
* Confidence score display
* Detection of multiple capsule colors (e.g., White–Blue, White–Red/Pink)

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
Final Video with
Bounding Boxes + IDs + Colors
```

---

# 📊 Model Performance

| Metric       |      Value |
| ------------ | ---------: |
| Precision    | **0.9875** |
| Recall       | **0.9824** |
| mAP@0.5      | **0.9942** |
| mAP@0.5:0.95 | **0.9461** |

---

# 🛠️ Technologies

* Python 3.12
* YOLO11n (Ultralytics)
* ByteTrack
* OpenCV
* NumPy

---

# 📸 Sample Detection Results

Random detection examples from the trained model.

| Detection 1                | Detection 2                | Detection 3                |
| -------------------------- | -------------------------- | -------------------------- |
| ![](images/detection1.jpg) | ![](images/detection2.jpg) | ![](images/detection3.jpg) |

| Detection 4                | Detection 5                | Detection 6                |
| -------------------------- | -------------------------- | -------------------------- |
| ![](images/detection4.jpg) | ![](images/detection5.jpg) | ![](images/detection6.jpg) |

---

# 🎥 Demo

The output video includes:

* Real-time capsule detection
* Unique tracking IDs
* HSV-based color classification
* Confidence scores

Example output:

```
ID: 12
Color: White-Blue
Confidence: 0.98
```

---

# 📁 Project Structure

```text
YOLO11-Pill-Detection-Color-Tracking-System/
│
├── images/
│   ├── detection1.jpg
│   ├── detection2.jpg
│   ├── detection3.jpg
│   ├── detection4.jpg
│   ├── detection5.jpg
│   └── detection6.jpg
│
├── videos/
│   └── capsule_tracking_color.mp4
│
├── models/
│   └── best.pt
│
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

# 💡 Applications

* Pharmaceutical quality control
* Automated production line inspection
* Smart manufacturing
* Industrial computer vision
* Medical packaging inspection

---

# 📄 License

This project is released for educational and research purposes.
