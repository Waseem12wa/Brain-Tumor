# 🧠 Brain Tumor Detection Using YOLOv10 🚀

An advanced deep learning project that detects brain tumors from MRI scans using the **YOLOv10** object detection algorithm. The model leverages computer vision, PyTorch, and Roboflow datasets for fast, accurate, and real-time localization of tumors in medical images.

---

## 📌 Project Overview

Brain tumor detection is a crucial task in medical diagnostics. Timely and precise identification can significantly improve treatment outcomes. This project automates the tumor detection process using **YOLOv10**, the latest version of the YOLO family, known for its speed and efficiency.

---

## ⚙️ Technologies Used

- Python  
- [YOLOv10](https://github.com/WongKinYiu/yolov10) (You Only Look Once v10)  
- PyTorch  
- Ultralytics API  
- Roboflow  
- Google Colab  
- Gradio (for interactive UI)  
- Matplotlib & OpenCV (for visualization)

---

## 🗃 Dataset

- **Source**: Roboflow  
- **Type**: Brain MRI images (labeled)  
- **Classes**: Tumor (Single-class object detection)  
- **Format**: YOLOv8-compatible (used for YOLOv10 training)  
- **Split**: Training, Validation, Test sets  
- **Access**: Imported via Roboflow Python API

---

## 🧠 Model: YOLOv10

**YOLOv10** is optimized for:

- Real-time object detection  
- Low-latency and lightweight deployment  
- High accuracy with small model sizes  

We used the `yolov10n.pt` (nano version) as a base for **transfer learning**, making the model fast and suitable for deployment on edge devices.

---

## 🔧 Workflow

### 🗂 Data Preparation
- Dataset loaded via Roboflow
- Converted to YOLO format (YOLOv8-compatible)

### 📈 Model Training
- Trained for 25–50 epochs
- Evaluated using: Loss, Precision, Recall, mAP

### 🧪 Prediction & Visualization
- Predictions on unseen validation images
- Visualized results using Matplotlib

### 💻 Gradio Web App
- Interactive UI built with Gradio
- Users can upload MRI images and get instant predictions
- Annotated tumor regions displayed in real-time

---

## 📊 Results

- High-precision localization of tumors
- Fast inference (even on Google Colab free tier)
- Accessible web UI for non-technical users

---

## 🌐 Future Improvements

- Upgrade to larger models (`yolov10s`, `yolov10m`) for improved accuracy
- Add Flask or Django backend for full-stack web deployment
- Export model to ONNX or TFLite for mobile/embedded use
- Extend dataset to **multi-class classification** (e.g., meningioma, glioma)

---

## 📽 Demo

- 🧠 Real-time detection notebook  
- 📷 Visualizations on test images  
- 🌐 Live Gradio web app for hands-on testing

---

## 📎 License

This project is for educational and research purposes. Licensing depends on the dataset and model usage.

---

## 🤝 Contributions

Contributions, feedback, and suggestions are welcome! Feel free to fork and enhance this project.

---
