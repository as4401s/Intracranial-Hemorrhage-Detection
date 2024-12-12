# Intracranial Hemorrhage Detection

## Overview

This repository provides tools and resources for detecting intracranial hemorrhages from medical imaging data, using state-of-the-art machine learning techniques. It is designed to facilitate the development, training, and evaluation of models for this critical medical diagnosis task. The project is structured for both ease of use and extensibility, catering to researchers, practitioners, and developers in the medical imaging domain.

## Features
- **Data Preprocessing**: Tools for handling medical imaging datasets, including loading, augmentation, and normalization.
- **Model Training**: Scripts to train deep learning models for intracranial hemorrhage detection.
- **Evaluation Metrics**: Code to compute key performance metrics such as accuracy, sensitivity, specificity, and AUC (Area Under the Curve).
- **Visualization**: Utilities to visualize model predictions alongside the original images for interpretability.
- **Extensible Architecture**: Easily add new models, datasets, or preprocessing steps.

## Requirements

### Hardware
- GPU with CUDA support (recommended for training)

### Software
- Python 3.8 or later
- Required libraries:
  - TensorFlow 
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - OpenCV (optional, for image preprocessing)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/as4401s/Intracranial-Hemorrhage-Detection.git
   cd Intracranial-Hemorrhage-Detection
