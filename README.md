# 🛣️ Pothole Detection System using YOLOv5

A computer vision-based solution for detecting potholes on roads using the YOLOv5 object detection algorithm. This project automates the detection of potholes from road images, helping authorities address maintenance issues faster and more accurately.

## 📄 Abstract

Potholes are a major cause of road accidents and vehicle damage, especially on Indian roads. Manual inspection methods are time-consuming and inefficient. To solve this, we developed a deep learning model using **YOLOv5**, a real-time object detection framework, to automatically identify potholes in road images with high accuracy and speed.

## 👩‍💻 Authors

- Shylee Veronica  
- **Poojashree Chandrashekar**  
- Himangshu Das  
- Mangesh Thakur  
- *Guided by Dr. Mallikarjun K., REVA University, Bengaluru*

## 🧠 Technologies Used

- **YOLOv5** (You Only Look Once version 5)
- Python (PyTorch, OpenCV)
- Computer Vision & Deep Learning
- Bounding box localization and confidence scoring

## 🧪 Methodology

- Input image is divided into a grid (S x S), where each cell predicts:
  - B anchor boxes
  - Class probability scores
  - Bounding box coordinates
- YOLOv5 performs:
  - Single-pass forward propagation
  - Non-Max Suppression to avoid duplicate detections
- Real-time detection results in bounding boxes around potholes with confidence levels.

## 📊 Results

- Successfully detected potholes using bounding boxes in varied conditions
- Visual results demonstrated high confidence scores and accurate localization
- Model showed real-time processing capability with consistent accuracy

## 🚀 Future Work

- Collaborate with civic authorities to integrate system into road maintenance operations
- Enable live alert generation and pothole mapping using GPS tagging
- Expand detection to include road humps and cracks


## 🔗 References

Key references include:
- [YOLOv5 by Ultralytics](https://github.com/ultralytics/yolov5)
- Road Accidents in India 2021 Report
- Research from IEEE and other peer-reviewed publications on object detection and road condition monitoring

## 📌 Keywords

`pothole detection`, `YOLOv5`, `computer vision`, `object detection`, `deep learning`, `smart infrastructure`



