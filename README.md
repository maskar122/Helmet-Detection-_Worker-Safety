# Worker Safety Detection using YOLOv5 🦺

## 📌 Overview
This project focuses on **worker safety** by detecting whether workers are wearing safety helmets.  
The model is based on **YOLOv5**, trained on a custom dataset of images labeled for helmets and workers.  
The aim is to help improve workplace safety by automatically detecting unsafe conditions in real time.  

---

## 🚀 Features
- Detects if workers are wearing **helmets** or not.  
- Real-time object detection using **YOLOv5**.  
- Can be applied to both **images** and **videos**.  
- Custom-trained model with dataset relevant to worker safety.  

---

## 📂 Project Structure

├── data/ # Dataset YAML & configs

├── runs/ # Training & detection results (not uploaded here)

├── yolov5/ # YOLOv5 framework

├── best.pt # Trained model weights (upload if <100MB)

├── requirements.txt # Required Python packages

├── train.py # Training script

├── detect.py # Detection script

├── val.py # Validation script

└── README.md # Project description

---

# 📊 Results

Example detection result:

![worker-safety-detection](https://github.com/maskar122/Helmet-Detection-_Worker-Safety/blob/37617df13145389120cc99c48c7496d3c3312939/images/005303_jpg.rf.cce32679b8fede85699505a2f2624366.jpg)
![worker-safety-detection](https://github.com/maskar122/Helmet-Detection-_Worker-Safety/blob/37617df13145389120cc99c48c7496d3c3312939/images/005317_jpg.rf.20f63f28ecb6518c66123c2341b674ee.jpg)
![worker-safety-detection](https://github.com/maskar122/Helmet-Detection-_Worker-Safety/blob/37617df13145389120cc99c48c7496d3c3312939/images/005490_jpg.rf.c013d7ad031150c2a323fead3305fae9.jpg)

---
# 🎯 Use Cases

Monitoring construction sites for worker safety.

Automated alerts for non-compliance with safety gear.

Improving occupational safety standards.
