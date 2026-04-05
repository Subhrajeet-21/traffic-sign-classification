# 🚦 Traffic Sign Detection & Classification using MobileNetV2

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.10-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview
This project focuses on **Traffic Sign Detection and Classification** using **Deep Learning (MobileNetV2)**.  
The model is trained on a dataset containing **55 different traffic sign classes** and achieves high accuracy.

---

## 🎯 Key Features
- Image classification using **MobileNetV2**  
- Data augmentation for better performance  
- Early stopping & model checkpointing  
- Evaluation using accuracy, precision, recall, F1-score  
- Confusion matrix & ROC-AUC analysis  

---

## 📂 Dataset
- Contains **~4000+ images**
- Total **55 classes**
- Organized into:
  - `train/`
  - `test/`

> ⚠️ Dataset is not included due to GitHub size limitations.

📥 Download Dataset:  [Dataset link](https://drive.google.com/drive/folders/1DdcQY8BYDj1-ImzMlw5gpLbQYaPR2SRJ?usp=sharing)

After downloading, extract and place it.

---

## Tech Stack
-  Python
-  TensorFlow / Keras
-  OpenCV
-  Matplotlib
-  NumPy
-  Scikit-learn

---

## Model Architecture
- Base Model: **MobileNetV2 (Pretrained on ImageNet)**
- Layers:
  - Global Average Pooling
  - Dense (128, ReLU)
  - Dropout (0.3)
  - Output Layer (Softmax)

---

## Training Details
- Image Size: `224x224`
- Batch Size: `32`
- Optimizer: `Adam`
- Loss Function: `Categorical Crossentropy`
- Epochs: `50`

---

## 📊 Results

| Metric        | Value |
|--------------|------|
| Accuracy      | **93.57%** |
| Precision     | 0.9386 |
| Recall        | 0.9357 |
| F1 Score      | 0.9349 |

---

## 📉 Training Graph
### Training Performance
<img width="1026" height="599" alt="Screenshot 2026-04-05 200311" src="https://github.com/user-attachments/assets/297bdd27-a464-4602-8b14-4b88fc963230" />

### Confusion Matrix
<img width="918" height="856" alt="Screenshot 2026-04-05 200247" src="https://github.com/user-attachments/assets/56cac3d9-7adb-40b4-a0a9-1267ae466486" />

### Sample Predictions
<img width="918" height="515" alt="Screenshot 2026-04-05 200528" src="https://github.com/user-attachments/assets/8f1f5db3-c284-4f01-9f65-73d0f49ff035" />

### ROC Curve
<img width="904" height="1110" alt="Screenshot 2026-04-05 200342" src="https://github.com/user-attachments/assets/c0c851c8-8df9-4549-bb91-adbfbf6d5628" />

---

## Model Evaluation
- Confusion Matrix
- Classification Report
- ROC-AUC Curve

---

## 🧪 Testing
- Random test image predictions
- Full dataset evaluation
- Final Test Accuracy: **93.57%**

---
