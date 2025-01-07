
# Alzheimer’s Disease Diagnosis using CNN 

![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Model Performance](#model-performance)
  - [Transfer Learning with DenseNet-121](#transfer-learning-with-densenet-121)
  - [K-Fold Cross-Validation](#k-fold-cross-validation)
  - [ROC-AUC Score](#roc-auc-score)
- [Snapshots](#snapshots)
  - [ROC-AUC Curve](#roc-auc-curve)
  - [Front-End Interface](#front-end-interface)
- [Acknowledgements](#acknowledgements)

## Introduction

This project presents an innovative approach to diagnosing Alzheimer's disease by integrating advanced deep learning methods, optimization techniques, and medical image processing. It specializes in multi-class classification to distinguish between Alzheimer's Disease (AD), Mild Cognitive Impairment (MCI), and Cognitively Normal (CN) stages using MRI scans, enabling earlier detection and improving diagnostic precision. Leveraging transfer learning with the DenseNet-121 model pre-trained on the RadImageNet database, the solution aims to enhance patient outcomes through more accurate diagnoses. The application includes a user-friendly interface that supports easy image uploads and delivers instant classification results, making it highly suitable for clinical applications.


## Features

- **Transfer Learning with DenseNet-121**: Implements the DenseNet-121 architecture pre-trained on the RadImageNet database for enhanced feature extraction from medical images.
- **K-Fold Cross-Validation**: Ensures model accuracy and robustness through k-fold cross-validation across various data subsets.
- **High Accuracy**: Delivers a test accuracy of 95.13%, providing reliable and precise multi-class classification.
- **User-Friendly Interface**: Offers a simple and intuitive front-end for uploading medical images and viewing classification results.
- **Real-time Classification**: Provides instant feedback and classification results upon image submission.
- **Performance Metrics**: Includes a ROC-AUC curve to effectively illustrate the model's diagnostic performance and efficacy.


## Model Performance

The model achieved a **test accuracy of 95.13%**, demonstrating its high reliability in classifying MRI scans into Alzheimer's Disease (AD), Mild Cognitive Impairment (MCI), and Cognitively Normal (CN) stages.

### Transfer Learning with DenseNet-121

**Pre-trained on RadImageNet**: 
- Utilizes the DenseNet-121 model pre-trained on the RadImageNet database, specifically curated for medical imaging tasks.
- Enhances feature extraction from MRI scans, leveraging domain-specific knowledge to boost performance.

**Transfer Learning Benefits**: 
- Reduces training time by starting with a pre-trained model that already possesses relevant knowledge.
- Improves overall performance and accuracy by building on the strengths of the pre-trained model.


### K-Fold Cross-Validation

- Implements k-fold cross-validation to validate the model's consistency across various data subsets.
- Ensures the model's results are generalizable to unseen datasets, enhancing reliability.

### ROC-AUC Score

- Evaluates model performance using the Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) metric.
- Achieves an exceptional **ROC-AUC score of 0.99**, indicating high efficacy in differentiating between Alzheimer's Disease stages.

## Snapshots

### ROC-AUC Curve

<img width="717" alt="Screenshot 2024-10-11 at 2 26 13 AM" src="https://github.com/user-attachments/assets/35eec27a-ee3f-40d2-b695-03ab573853f0">

The ROC-AUC curve demonstrates the trade-off between the sensitivity and the specificity at various threshold settings.

### Front-End Interface

<img width="1512" alt="Screenshot 2024-10-11 at 2 22 48 AM" src="https://github.com/user-attachments/assets/a36e36ea-d8f5-4bbb-a664-24d633c696a3">

<img width="1512" alt="Screenshot 2024-10-11 at 2 23 30 AM" src="https://github.com/user-attachments/assets/8a1efbd1-4dec-4e89-9e0e-9b6cf7674a45">

The user-friendly interface enables seamless image uploads and provides instant diagnostic results.

## Acknowledgements

- **Dataset**: Special thanks to [ADNI](https://adni.loni.usc.edu) for providing the MRI images used in training and testing.
- **RadImageNet**: Utilized the [RadImageNet](https://github.com/BMEII-AI/RadImageNet) database to pre-train the DenseNet-121 model for medical imaging tasks.
- **Libraries and Frameworks**: Built using TensorFlow, Keras, Flask, and other open-source libraries.



