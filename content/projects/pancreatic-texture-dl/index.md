---
title: Deep Learning-Based Quantification of Pancreatic Texture Using IR-Spectroscopy Data
date: 2023-10-26
tags:
  - Deep Learning
  - Medical Imaging
  - Computer Vision
  - PyTorch
  - ResNet
  - MLOps
featured: false

links:
  - type: github
    url: "https://github.com/Tulin206/thesis"
---

## Project Overview

Developed an AI-powered system to analyze pancreatic tissue textures and tumor grades using infrared spectroscopy data, assisting surgeons in assessing pancreatic cancer and post-operative fistula risk.

<!--more-->

## Key Achievements

- **Clinical Impact**: Collaborated with oncologists at NCT Dresden to develop methodologies with real clinical applications
- **High Accuracy**: Achieved over 90% classification accuracy using ResNet18 on IR spectroscopic images
- **Multimodal Analysis**: Integrated IR spectroscopic images with tumor grade data and applied PCA for dimensionality reduction
- **Dataset**: Processed data from 30 patients collected at a university hospital
- **Model Variants**: Implemented and compared scratch-built and pre-trained models including ResNet18 and MobileNetV1

## Technical Highlights

### Data Processing
- Cleaned and integrated data from multiple clinical sources
- Built robust classification datasets addressing class imbalance
- Applied quality assurance and validation workflows

### Deep Learning Models
- **Primary Architecture**: ResNet18 (90%+ accuracy)
- **Alternative Models**: MobileNetV1 for efficient inference
- **Framework**: PyTorch with interpretability using Captum

### Advanced Techniques
- Dimensionality reduction (PCA) to handle dataset limitations
- Multimodal data integration for enhanced predictions
- Semi-supervised learning approaches

### MLOps & DevOps
- Version control with GitLab
- Model versioning using DVC (Data Version Control)
- CI/CD pipelines for automated workflows
- TensorBoard integration with PyTorch for drift analysis
- Automated monitoring when introducing new datasets

## Technologies Used

**Core Libraries**: Python, NumPy, Pandas, Matplotlib, PyTorch, TensorFlow, Keras, Scikit-Learn

**Tools**: PyCharm, Captum (interpretability), PCA, CI/CD pipelines, Git/GitLab

**Techniques**: Deep Learning, Computer Vision, Supervised & Semi-supervised Learning

## Research Collaboration

- **Institution**: Helmholtz-Zentrum Dresden-Rossendorf (HZDR) & NCT Dresden
- **Advisor**: Prof. Dr. Stefanie Speidel
- **Clinical Partners**: Oncology Department

## Impact

This project demonstrates the application of advanced deep learning techniques to solve real-world clinical problems, with direct implications for surgical planning and patient outcomes in pancreatic cancer treatment.

---

*This project involves confidential medical data and is presented with appropriate privacy considerations.*
