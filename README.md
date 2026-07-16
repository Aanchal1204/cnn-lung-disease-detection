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

## Model Comparison

| Model | Accuracy |
|--------|----------|
| EfficientNetB0 | **85.6%** |
| DenseNet121 | 84% |
| ResNet50 | 53% |

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
