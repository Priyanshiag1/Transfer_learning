# Pneumonia Detection using Transfer Learning (ResNet50)

This deep learning project classifies chest X-ray images into **Normal** or **Pneumonia** using a **pretrained ResNet50 model**. It leverages transfer learning to handle the limited dataset size while achieving high performance.

---

## 🧠 Model Overview

- 🔍 **Base Model**: ResNet50 pretrained on ImageNet
- 🧊 **Stage 1**: Freeze base model, train only top classification layers
- 🔥 **Stage 2**: Unfreeze last 30 layers of ResNet50 and fine-tune on X-ray images
- 🩻 **Input Size**: 224x224 RGB images
- 🏷️ **Classes**: 
  - `NORMAL` 
  - `PNEUMONIA`

---

## 📂 Dataset

- **Source**: [Kaggle - Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
---

## 🛠️ Features & Workflow

- ✅ Image preprocessing and augmentation using `ImageDataGenerator`
- ✅ Model building using TensorFlow and Keras
- ✅ Early stopping and model checkpointing
- ✅ Performance visualization (accuracy/loss plots)
- ✅ Final prediction on a custom image with confidence score
- ✅ Grad-CAM for visual explanation of predictions 🔍

---
