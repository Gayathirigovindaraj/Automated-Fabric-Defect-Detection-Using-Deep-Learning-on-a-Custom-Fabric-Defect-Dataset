# Automated-Fabric-Defect-Detection-Using-Deep-Learning-on-a-Custom-Fabric-Defect-Dataset
Deep learning-based fabric defect detection using YOLOv8 with performance comparison, training analysis, and visualization. Includes research implementation, dataset insights, and evaluation metrics.
# 🧵 Automated Fabric Defect Detection using YOLOv8

## 📌 Overview
This project focuses on **automated fabric defect detection** using deep learning techniques. It implements and analyzes **YOLOv8-based object detection** and compares model performance using training metrics and visual outputs.

The project is based on a research study and includes:
- Model implementation (Python - Jupyter Notebook)
- Performance comparison (YOLOv7 vs YOLOv8)
- Output visualizations (graphs)
- Research paper documentation

---

## 🎯 Objectives
- Detect fabric defects automatically using deep learning
- Improve accuracy over traditional inspection methods
- Analyze model performance using metrics like:
  - Accuracy
  - Precision & Recall
  - mAP (Mean Average Precision)
- Visualize training and evaluation results

---

## 🧠 Methodology
The system uses a **YOLOv8-based architecture** with:
- **Backbone:** ResNet-101
- **Neck:** Feature Pyramid Network (FPN)
- **Loss Functions:**
  - CIoU Loss (Bounding Box)
  - Focal Loss (Class imbalance handling)

The model is trained on a **custom Fabric Defect Dataset (FDD)** containing:
- 10,000 images
- 6 defect classes:
  - Hole
  - OilStain
  - WarpBreak
  - WeftCrack
  - Slub
  - ColorYarn

---

## ⚙️ Technologies Used
- Python
- Jupyter Notebook
- PyTorch
- OpenCV
- Matplotlib
- YOLOv7 & YOLOv8

---

## 📊 Results
- ✅ Accuracy: **95.85%**
- ✅ mAP: **0.92**
- ✅ Precision: **0.94**
- ✅ Inference Speed: **48 FPS**

### 📈 Key Observations
- YOLOv8 outperforms YOLOv7 and Faster R-CNN
- Better detection of small defects
- Improved real-time performance

---

## 📉 Output Visualizations
The project includes:
- Training Loss Graph
- Precision vs Recall Curve
- Model Comparison Graph (YOLOv7 vs YOLOv8)
- Confusion Matrix

---

## 📁 Project Structure
