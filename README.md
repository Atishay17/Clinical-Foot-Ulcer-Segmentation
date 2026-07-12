# Clinical Foot Ulcer Segmentation
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Medical Imaging](https://img.shields.io/badge/Medical-Imaging-009688?style=for-the-badge)
![Research](https://img.shields.io/badge/Status-Research-blue?style=for-the-badge)

> Deep learning-based clinical image segmentation using multiple CNN-based U-Net architectures for accurate wound delineation and comparative performance evaluation.

---

## 📌 Project Overview

Clinical wound segmentation plays a vital role in computer-aided diagnosis by enabling accurate localization of affected regions and supporting treatment planning. This research project presents a comprehensive comparative study of multiple CNN-based U-Net architectures for automated medical image segmentation.

The study evaluates several encoder-decoder architectures under identical experimental settings and investigates the impact of data augmentation on segmentation performance.

---

## 🎯 Objectives

- Develop an automated medical image segmentation pipeline.
- Compare multiple U-Net variants for segmentation accuracy.
- Evaluate the impact of data augmentation on model performance.
- Analyze segmentation quality using standard medical imaging metrics.

---

## 🧠 Models Evaluated

- U-Net
- U-Net++
- Double U-Net
- Dense U-Net
- ResNet U-Net
- VGG U-Net
- U²-Net

---

## 🗂 Dataset

This research utilizes the **PH² dermoscopic image dataset**, a publicly available benchmark dataset containing expert-annotated lesion masks for medical image segmentation research.

Dataset split:

- Training: 70%
- Validation: 15%
- Testing: 15%

---
### Workflow

<p align="center">
<img src="images/workflow.png" width="90%">
</p>

## ⚙️ Methodology

The complete workflow consists of:

1. Image preprocessing
2. Data augmentation
3. Model training
4. Segmentation prediction
5. Quantitative evaluation

---

## 📊 Evaluation Metrics

Performance was evaluated using:

- Dice Coefficient
- Intersection over Union (IoU)
- Mean Absolute Error (MAE)
- Hausdorff Distance
- Average Symmetric Surface Distance (ASSD)
- Davies–Bouldin Index

---
## 📈 Performance Summary

| Model | Dice | IoU |
|------|------:|------:|
| U-Net | 0.9390 | 0.8850 |
| Double U-Net | 0.9751 | 0.9514 |
| U²-Net | 0.9787 | 0.9583 |
| VGG U-Net | 0.9787 | 0.9583 |
| U-Net++ | 0.9733 | 0.9479 |
| ResNet U-Net | **0.9875** | **0.9754** |
| Dense U-Net | 0.9802 | 0.9612 |

## Sample Segmentation Results

<p align="center">
<img src="images/results.png" width="95%">
</p>

## 🚧 Repository Status

This repository accompanies an ongoing research project.

To preserve the novelty of the work while the manuscript is under peer review, the following components remain private:

- Source code
- Training pipeline
- Model weights
- Experiment notebooks
- Dataset preparation scripts

These resources will be released after publication or when permitted.

---

## 🛠 Technologies

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Medical Image Processing

---

## 👤 Author

**Atishay Jain**

Research Project in Medical Image Segmentation
