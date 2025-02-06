# Anomaly Detection in Surveillance Videos
## Overview
This project leverages deep learning for detecting unusual activities in surveillance videos. Using a 3D ResNet-18 architecture, the model learns spatial and temporal features to distinguish between normal and anomalous events across 13 anomaly categories.

## Features
- Real-time anomaly detection for enhanced security surveillance
- 3D CNN-based approach for learning motion and spatial patterns
- Preprocessing pipeline with frame extraction, augmentation, and segmentation
- Performance evaluation with precision, recall, F1-score, and confusion matrices
- PyTorch implementation with OpenCV and deep learning libraries

## Performance
- Accuracy: 66.8%
- Precision: 67%
- Recall: 43.5%
- F1-score: 63%
## Methodology
- Frame Extraction: Convert videos into 32 fixed-length frames.
- Feature Learning: Utilize 3D ResNet-18 to capture spatiotemporal patterns.
- Training & Evaluation: Train on a large-scale dataset with standard evaluation metrics.
- Optimization: Data augmentation and preprocessing to improve robustness.
## Technologies Used
### Framework: 
PyTorch
### Libraries: 
OpenCV, NumPy, Pandas, Matplotlib
### Model: 
3D ResNet-18
### Development: 
Google Colab
## Dataset
The model is trained on a balanced dataset consisting of images for the sixth issue of the Saudi Arabian currency banknotes. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mateohervas/dcsass-dataset).
## Paper
https://drive.google.com/file/d/1Uq8vlYDl1wO100g31ImUA_tJhPSDGorW/view?usp=sharing
