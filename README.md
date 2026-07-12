# Clinical Foot Ulcer Segmentation

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

## 🚧 Repository Status

The associated research manuscript is currently under peer review.

To protect the novelty of the research, the following components are currently private:

- Training source code
- Model implementations
- Dataset preparation pipeline
- Trained model weights
- Experimental notebooks

These materials will be released after publication or when permitted.

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
