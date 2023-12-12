# AI Models for Handwriting Digit Recognition 🤖✍️

## 🌟 Project Overview
This project focuses on comparing Artificial Neural Networks (ANN) and k-Nearest Neighbors (kNN) for classifying handwritten digits.

## 🎯 Key Objectives
- **Create a test dataset** of handwritten digits.
- **Analyze and compare** the performance of ANN and kNN on this dataset.

## 🛠️ Methodology
- Digits (0-9) drawn digitally, resized to 28x28 pixels to match MNIST dimensions.
- Nearest neighbors from MNIST identified using kNN (dot product similarity, weighted voting).
- Analysis with various `k` values and similarity metrics.
- Utilised Principal Component Analysis (PCA) to improve kNN efficiency.

## 💡 Conclusion Summary
- **kNN outperformed ANN**: Achieving an accuracy of 70% compared to ANN's 55%.
- **PCA Integration**: Enhanced kNN's processing efficiency by reducing feature dimensions.
- **Classification Reports Indicate**:
  - Both models struggled with digit '9'.
  - kNN showed varied performance across different datasets.
  - Possible data imbalance in the neighbors dataset.
  - ANN potentially overfitted, with room for parameter optimization.

## 🌈 Final Insights
The project highlights the strengths and limitations of both ANN and kNN in digit classification, especially the challenges with certain digits like '9'. Further details and classification reports are provided in the collab doc.
