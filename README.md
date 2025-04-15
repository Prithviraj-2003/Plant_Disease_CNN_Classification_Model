# 🌿 Plant Disease Classification using CNN (ResNet9)

This project focuses on building a **Convolutional Neural Network (CNN)** to classify plant diseases from leaf images. The model is inspired by a custom **ResNet9 architecture**, which achieved an impressive **99% accuracy** on the full Plant Disease dataset.

## 🧠 Project Highlights

- Built a custom CNN using PyTorch
- Used a ResNet-style architecture with skip connections
- Achieved **99% test accuracy** on Kaggle’s PlantVillage dataset
- Trained from scratch (no pretrained models)
- Saved the final trained model as `.pth` for future use

---

## 📂 Dataset

- **Name**: Plant Disease Dataset
- **Source**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
- **Classes**: 38 plant disease categories
- **Total Images**: ~54,000
- All images were loaded directly by converting them into tensors no transformations used.

---

## 🧠 Model Architecture

- Custom ResNet9-style CNN:
  - Uses `Conv2D + BatchNorm + ReLU`
  - Includes **skip connections** for better gradient flow
  - Downsampling using **MaxPool2D**
  - Final classification with `Linear` layer after flattening

You can find the full model in the notebook.

---

## 📈 Results

- **Training Accuracy**: ~99%
- **Validation Accuracy**: ~98-99%
- Trained using **Kaggle GPU runtime** for faster processing

---
