# Alzheimer’s Disease Detection using Deep Learning

## Project Overview

This project aims to detect Alzheimer's Disease (AD) from MRI images using **Deep Learning** techniques. Specifically, the system uses **Convolutional Neural Networks (CNN)** to classify MRI images into different stages of Alzheimer's Disease:

- Mild Demented
- Moderate Demented
- Non-Demented
- Very Mild Demented

### Abstract

Alzheimer's Disease (AD) is a progressive neurodegenerative disorder that leads to cognitive decline and dementia. Early detection is crucial for timely intervention. In this study, MRI scans are used to classify Alzheimer's Disease using a CNN model, achieving a training accuracy of **86.34%** and validation accuracy of **86.45%**.

---

## Existing System vs Proposed System

### Existing System
Existing methods for Alzheimer's detection rely on traditional machine learning algorithms, such as Support Vector Machines (SVM) and Fisher Discriminant Analysis (FDA). These systems face issues such as:
- Small sample sizes
- Noisy data
- Unverified pathological data

### Proposed System
The proposed system uses **Deep Learning**, specifically CNNs, to automatically classify MRI scans. This approach is more robust and scalable, achieving higher accuracy in predicting Alzheimer's stages with the Kaggle dataset.

---

## Advantages of Proposed System

1. **Early Diagnosis**: Detects Alzheimer's Disease in its early stages, improving clinical outcomes.
2. **Accuracy**: CNNs are highly effective in pattern recognition tasks, ensuring reliable classification.
3. **Automated Process**: Reduces human error and provides an efficient, scalable solution for healthcare providers.

---

## System Requirements

### Hardware Requirements
- **System**: Pentium i3 Processor
- **RAM**: 4 GB
- **Hard Disk**: 500 GB
- **Monitor**: 15" LED
- **Input Devices**: Keyboard, Mouse

### Software Requirements
- **Operating System**: Windows 10
- **Python Version**: 3.8
- **Frameworks**: Flask (for deployment), TensorFlow/Keras (for deep learning)
- **Libraries**: numpy, pandas, matplotlib, scikit-learn

---

## Installation Instructions

### 1. Clone the Repository
Clone the project to your local machine:
```bash
git clone https://github.com/pranshu-jais/alzheimers-disease-detection.git
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
## Running the System
### 1. Train the Model
To train the CNN model on the Kaggle MRI dataset : https://www.kaggle.com/datasets/ninadaithal/imagesoasis , run the following command:
```bash
python train_model.py
```
### 2. Run the Application
Start the web application using Flask:
```bash
python app.py
```
