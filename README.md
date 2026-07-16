# Lung Disease Classification using Deep Learning

## Overview

This project performs multiclass lung disease classification using Chest X-ray images.

Three pretrained CNN models were compared:

- EfficientNetB0
- DenseNet121
- ResNet50

The goal is to determine which architecture performs best for automatic lung disease diagnosis.

---

## Dataset

The project classifies five categories:

- COVID-19
- Bacterial Pneumonia
- Viral Pneumonia
- Tuberculosis
- Normal

Dataset Source:
https://www.kaggle.com/datasets/omkarmanohardalvi/lungs-disease-dataset-4-types

---

## Technologies

- Python
- TensorFlow
- Keras
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Performance Comparison

The figure below compares the performance of EfficientNetB0, DenseNet121, and ResNet50 across multiple evaluation metrics.

- Overall Accuracy
- Class-wise Precision
- Class-wise Recall
- Class-wise F1-Score

EfficientNetB0 achieved the best overall performance, obtaining an accuracy of **85.6%**, followed closely by DenseNet121 (**84%**). ResNet50 performed significantly lower on this dataset.

<p align="center">
  <img src="results/Unknown.png" alt="Model Comparison" width="900">
</p>

## Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|:--------:|:---------:|:------:|:--------:|
| **EfficientNetB0** | **85.6%** | **85%** | **85%** | **85%** |
| **DenseNet121** | **84%** | **84%** | **84%** | **84%** |
| **ResNet50** | **53%** | **54%** | **53%** | **50%** |

---

## Workflow

1. Data Collection
2. Image Preprocessing
3. Data Augmentation
4. Transfer Learning
5. Model Training
6. Fine-Tuning
7. Evaluation
8. Prediction

---

## Repository Structure

```
notebooks/
src/
models/
results/
images/
paper/
```

---

## Future Work

- Vision Transformers
- Grad-CAM
- Explainable AI
- Streamlit Deployment

---
