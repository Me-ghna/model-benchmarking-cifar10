# 📊 Pretrained CNN Model Comparison

This repository presents a comparative analysis of three popular pretrained Convolutional Neural Network (CNN) models applied to the CIFAR-10 dataset. The goal is to evaluate and compare performance on image classification.

## Models Compared
- VGG19
- ResNet50
- InceptionV3

## Dataset
- CIFAR-10: 60,000 32x32 colour images in 10 classes, with 6,000 images per class.
- Used standard training/testing split (50,000 / 10,000).

## Methodology
- All models were fine-tuned on the CIFAR-10 training set using transfer learning.
- Layers were unfrozen gradually to enable partial retraining.
- Data augmentation appliedusing ImageDataGenerator.
- Evaluation metrics: accuracy
  
## Results


> 🔍 Full analysis and graphs available in the `results/` folder.

## 📁 Repository Structure
