# Skin Lesion Classification using Computer Vision and Machine Learning

## 📌 Project Overview

This project is a Computer Vision and Machine Learning-based system for classifying skin lesions as **Benign** or **Malignant**. The system uses image processing techniques, texture feature extraction, and Support Vector Machine (SVM) classification to assist in skin cancer detection.

## 🚀 Features

* Image preprocessing using OpenCV
* Lesion segmentation using Otsu Thresholding
* Texture feature extraction using Gray Level Co-occurrence Matrix (GLCM)
* Classification using Support Vector Machine (SVM)
* Interactive web interface using Gradio
* Visualization of preprocessed and segmented images

## 🛠️ Methodology

1. Image Acquisition
2. Image Preprocessing

   * Grayscale conversion
   * Gaussian filtering
3. Lesion Segmentation

   * Otsu thresholding
4. Feature Extraction

   * Lesion area
   * GLCM Contrast
   * GLCM Energy
5. Classification using SVM
6. Real-time Prediction using Gradio

## 💻 Technologies Used

* Python
* OpenCV
* Scikit-image
* Scikit-learn
* NumPy
* Gradio
* Google Colab

## 📊 Model

* Algorithm: Support Vector Machine (SVM)
* Kernel: RBF
* Feature Scaling: StandardScaler
* Classes: Benign and Malignant
