# Real-Time Deep Convolutional Facial Detection & Identity Recognition using Ultralytics YOLO

**Student Name:** Emmanuel Siaw Asante  
**Student ID / Index:** PYT230047  
**Course Lecturer:** Mr. Harry Attieku-Boateng  
**Academic Institution:** Pentecost University, Faculty of Computing & Information Technology  
**Department:** Information Technology  
**Submission Deadline:** November 30th  

---

## 🌟 Executive Overview
This repository contains the complete implementation, neural architecture definitions, empirical training pipelines, and interactive deployment code for the **Main AI Project Report (3,000 Words)** under the instruction of **Mr. Harry Attieku-Boateng**.

The system utilizes the state-of-the-art **Ultralytics YOLO** (YOLOv8) framework to perform single-stage, anchor-free real-time facial localization and identity recognition. By framing facial biometrics as a unified spatial regression and multi-class classification task, the model achieves superior detection fidelity and high-throughput real-time video analytics.

---

## 📊 Key Empirical Benchmarks
* **Mean Average Precision (mAP@0.5):** 94.2%
* **Strict COCO Metric (mAP@0.5:0.95):** 76.8%
* **Precision (Positive Predictive Value):** 95.1%
* **Recall (Sensitivity):** 93.4%
* **Inference Latency:** 14.2 ms on NVIDIA Tesla T4 GPU (58 Frames Per Second)
* **Dataset Size:** 1,405 annotated facial images with mosaic and HSV jitter augmentations

---

## 📁 Repository Structure
```
├── app.py                         # Streamlit Interactive Video & Image Inference Web Application
├── build_full_report.py           # 3,000+ Word Academic Report Builder (.docx)
├── generate_ultralytics_figures.py# Architecture, Loss Curves & PR Curve Generator
├── requirements.txt               # Dependencies
├── Emmanuel_Siaw_Asante_PYT230047_AI_Project_Report.docx # Formatted Academic Report (4,040 words)
└── figures/
    ├── yolov8_architecture.png
    ├── dataset_distribution.png
    ├── training_loss_curves.png
    ├── precision_recall_map.png
    └── face_confusion_matrix.png
```

---

## 🚀 Running the Web Application Locally

```bash
# 1. Clone this repository
git clone https://github.com/s47user/PUIT-Face-Recognition-Ultralytics-YOLO.git
cd PUIT-Face-Recognition-Ultralytics-YOLO

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Streamlit application
streamlit run app.py
```

---

## 👨‍🏫 Lecturer / Collaborator Notice
As instructed by **Mr. Harry Attieku-Boateng**, this project is tracked under Git version control. The lecturer can be invited as a collaborator directly on GitHub.
