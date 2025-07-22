# Image Classification

This project explores image classification using both traditional machine learning and deep learning models, including SVMs and Convolutional Neural Networks (CNNs), such as LeNet, and transfer learning using VGG16, and ResNet50. The task involves classifying 10 classes of images using a labelled dataset, with a focus on performance, interpretability, and evaluation metrics.

## Overview

The project compares:

- **SVM (Support Vector Machine)** – A classic ML approach for classification.
- **CNNs** – Including:
  - LeNet (basic CNN)
  - VGG16 (pre-trained deep network)
  - ResNet50 (pre-trained deep network)

Evaluation was based on accuracy, confusion matrices, precision, recall, F1-score, training time, and model size.

## Results Summary

- **SVM**: 54.5% accuracy  
- **LeNet**: 49% accuracy (limited by input size)
- **VGG16**: 95% accuracy
- **VGG16 with augmentation**: Performed similarly to default model
- **ResNet50**: >99% accuracy (using transfer learning)  


See full analysis in the [Report](./Image_Classification_report.pdf).

## Files

- `image_classification.ipynb` – Main Google Colab notebook  
- `Sebastian_Lynch_Image_Classification_Report.pdf` – Coursework report  
- `cw_data.zip` – Dataset (**not included here**, see below)

## Dataset

The dataset (`cw_data.zip`, ~1.4 GB) is too large for GitHub. You can download it from the link below and upload it to your Google Drive:

**[Download cw_data.zip](https://drive.google.com/file/d/1RXtKTdWPYldieVTLQvQy_V_VyE9wv4pG/view?usp=drive_link)**

To use the notebook, open in Google Colab and have `cw_data.zip` in your google drive.
