# 🚦 Lane Detection using Semantic Segmentation and Object Detection

## 📌 Project Overview
This project focuses on **lane detection and surrounding object recognition** for autonomous driving systems.  
It combines **Semantic Segmentation (U-Net)** and **Object Detection (YOLOv3)** to accurately detect lanes, markings, pedestrians, traffic signs, trees/vegetation, and obstacles such as constructions.  

---

## 🎯 Objectives
- Detect and segment road lanes and their markings.
- Identify surrounding objects like pedestrians, traffic signs, trees, vegetation, and obstacles.
- Achieve high accuracy in both segmentation and object detection using deep learning.

---

## 🏗️ Methodology
We used **two different Deep Learning (CNN) architectures** for this project:  

1. **Semantic Segmentation with U-Net**  
   - Model: U-Net  
   - Purpose: Lane and lane-marking detection  
   - Accuracy: **91%**

2. **Object Detection with YOLOv3**  
   - Model: YOLOv3 (You Only Look Once v3)  
   - Purpose: Detect pedestrians, traffic signs, trees, vegetation, and obstacles  
   - Accuracy: **97%**

---

## ⚙️ Tech Stack
- **Languages**: Python  
- **Frameworks & Libraries**: TensorFlow / Keras, OpenCV, NumPy, Matplotlib  
- **Models**: U-Net, YOLOv3  
- **Tools**: Jupyter Notebook, Google Colab  

---

## 📂 Features
- 🚗 **Lane Detection** – Identifies lane boundaries and lane markings.  
- 🧍 **Pedestrian Detection** – Detects pedestrians on or near the road.  
- 🚧 **Obstacle & Construction Detection** – Alerts for construction zones or objects on the road.  
- 🌳 **Environment Awareness** – Detects vegetation, trees, and other surrounding objects.  
- ⚡ **High Accuracy Models** – U-Net (91%) and YOLOv3 (97%).  

---

## 📊 Results
- **U-Net (Semantic Segmentation)**: Achieved **91% accuracy** in lane detection.  
- **YOLOv3 (Object Detection)**: Achieved **97% accuracy** in detecting objects.  
- Effective integration of segmentation and detection models for robust real-world performance.  

---

## 🚀 Future Improvements
- Extend detection to more traffic elements like signals, road barriers, and moving vehicles.  
- Optimize models for real-time processing in embedded systems.  
- Experiment with newer architectures (YOLOv5, EfficientDet, DeepLabV3+).  

---

## 🙌 Contributors
- **Your Name** – Data Scientist / ML Engineer  

---

## 📜 License
This project is licensed under the MIT License – feel free to use and modify with attribution.
