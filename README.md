Deep Learning Models for Breast Cancer Detection using Mammographic Imaging

Abstract
Breast cancer is one of the leading causes of mortality, and early detection plays a crucial role in improving survival rates. This project applies deep learning models, particularly CNN and ResNet50, to classify mammographic images as benign or malignant. Advanced image preprocessing techniques, such as negative transformation, adaptive histogram equalization (AHE), and histogram of oriented gradients (HOG), were used to enhance tumor visibility. The ResNet50 model achieved the highest test accuracy of 97.84%, demonstrating strong generalization to unseen data, while the CNN model reached approximately 80% accuracy. The results indicate that negative image transformation enhances critical feature detection, leading to better classification performance.

Project Overview

This project focuses on developing and evaluating deep learning models to detect breast cancer in mammograms. The key steps include:

Dataset Preprocessing: Cleaning and balancing the dataset to improve model performance.
Image Enhancement: Applying AHE, negative transformation, and HOG to highlight tumor regions.
Model Development: Training CNN and ResNet50 models on original and preprocessed images.
Performance Evaluation: Comparing model accuracy, generalization, and robustness in detecting cancerous tissues.
The CBIS-DDSM dataset was used, containing 10,239 mammographic images with expert-annotated benign and malignant cases.

Usage Instruction
Dataset Download
The dataset can be accessed from:
 CBIS-DDSM Dataset
