# Istanbul Traffic Object Detection using YOLOv8

## 🚦 Project Overview

This project develops a real-time object detection system for traffic scenes in Istanbul using the YOLO (You Only Look Once) deep learning framework. It detects and classifies key traffic-related objects:

- 🚗 Car  
- 🚌 Bus  
- 🚲 Bicycle  
- 🏍️ Motorcycle  
- 🚶 Person  

The system aims to automate traffic surveillance, improve urban mobility analysis, and provide foundational tools for smart city applications.

---

## 🎯 Objective

- Build an efficient, lightweight object detection model to analyze Istanbul traffic scenes in real-time.  
- Automate traffic monitoring and support smart city infrastructure development.  
- Enable scalable detection for urban mobility insights.

---

## 🧠 Skills Learned

- Object detection with YOLOv8n (Nano variant)  
- Data annotation conversion (XML to YOLO format)  
- Frame extraction from videos using OpenCV  
- Image augmentation with Albumentations (flip, brightness, rotate, resize)  
- Model evaluation using Precision-Recall (PR) curves  
- Visualization of detections using bounding boxes  
- Model training and inference with PyTorch and Ultralytics libraries  

---

## 🛠️ Technologies Used

- Python 3.x  
- YOLOv8n (Ultralytics YOLO Nano model)  
- PyTorch (deep learning framework)  
- OpenCV (frame extraction and image manipulation)  
- Albumentations (robust image augmentation)  
- Pillow (PIL) for image processing  
- XML Parsing with `xml.etree.ElementTree`  
- Pathlib, Shutil, YAML, tqdm (file handling and pipeline management)  

---

## 🧪 Methodology

- Captured raw traffic videos from Istanbul streets.  
- Extracted individual frames and saved them as `.jpg` images.  
- Annotated images using XML bounding boxes.  
- Converted XML annotations to YOLO-compatible `.txt` format.  
- Applied image augmentations: horizontal flip, brightness adjustment, rotation, resizing.  
- Split dataset: 80% training, 20% validation.  
- Created `data.yaml` configuration file with class names and dataset paths.  
- Trained YOLOv8n model on annotated traffic data using Ultralytics.  
- Evaluated model performance with PR curves and visual bounding box metrics.  
- Ran inference on new test images and videos.

---

## 🖼️ Media Samples

### Before – Original Traffic Footage

Captured raw video input from Istanbul intersections.  
📁 `Video Withpout bboxes.mp4`

### After – YOLOv8 Detection Results

Detected cars, buses, motorcycles, bicycles, and people with bounding boxes.  
📁 `output Traffic Video.mp4`

---

## 🧠 YOLOv8n Model Details

- **Model:** YOLOv8n (Nano variant)  
- **Advantages:** Lightweight, efficient, 30% smaller size, ~80% performance compared to YOLO small  
- **Training Data:** Custom Istanbul traffic images, annotated and split manually  
- **Configuration:** Defined in `data.yaml` with 5 traffic-related classes

---
📬 Contact
For any questions, suggestions, or collaboration inquiries, please reach out:
📧 souaksoufyen@gmail.com

