# Envision_AI-ML

# Chest X-ray 3-Class Classifier (Normal, Pneumonia, Tuberculosis)

## Overview
This project implements a deep learning model to classify chest X-ray images into three categories: Normal, Pneumonia, and Tuberculosis.

## Dataset
- Normal + Pneumonia: paultimothymooney/chest-xray-pneumonia
- Tuberculosis: yasserhessein/tuberculosis-chest-x-rays-images

## Model
- CNN / EfficientNet-based model with Dropout and BatchNorm
- Pretrained on ImageNet
- Fine-tuned on the chest X-ray dataset

## Preprocessing
- Resize to 224x224
- Normalization
- Data augmentation (flips, rotations, zoom)

## Training & Evaluation
- Optimizer: AdamW
- Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
- Confusion matrix visualized

## Ethical Considerations
- Possible dataset bias
- Not a replacement for doctors
- Explainable via Grad-CAM

## How to Run
1. Open this notebook in Colab
2. Run all cells top to bottom
"""
