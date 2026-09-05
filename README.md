# Deep Learning-Based Pneumonia Detection from Chest X-Ray Images
## Summary
  ✅ Developed a deep learning pipeline for automated pneumonia detection from chest X-ray images.
  ✅ Compared seven pretrained CNN architectures: AlexNet, VGG16, Inception, MobileNet, ResNet, XceptionNet, and DenseNet.
  ✅ Used transfer learning, data augmentation, and class imbalance handling to improve model performance.
  ✅ Evaluated models using Accuracy, Sensitivity, and Specificity.
  ✅ Applied Grad-CAM to visualize regions contributing to model predictions.

## Objective

To investigate and compare different pretrained CNN architectures for pneumonia detection and identify their strengths in terms of overall classification performance and pneumonia detection sensitivity.

## Dataset
Normal: 1,341 images
Pneumonia: 3,875 images
Total: 5,216 images
Input size: 224 × 224 pixels

## Methodology
  ✔ Image preprocessing and normalization
  ✔ Data augmentation
  ✔ Class imbalance handling
  ✔ ImageNet-based transfer learning
  ✔ Binary classification
  ✔ Early stopping to reduce overfitting
  ✔ Grad-CAM for model interpretability

## Models
AlexNet | VGG16 | Inception | MobileNet | ResNet | XceptionNet | DenseNet

## Results

AlexNet (Highest) 
Accuracy: 91.03%
Sensitivity: 96.67%
Specificity: ~80%

VGG16
Accuracy: 90.06%
Sensitivity: 97.18%
Specificity: ~80%

## Key Findings

AlexNet achieved the highest reported accuracy, while VGG16 achieved slightly higher sensitivity.

This demonstrates that the model with the highest accuracy is not necessarily the model with the highest sensitivity, which is an important consideration in medical image classification.

## Explainable AI

Grad-CAM was used to visualize the image regions contributing to model predictions and provide insight into the model's decision-making process.

## Technologies

Python | PyTorch | Torchvision | Scikit-learn | NumPy | Matplotlib | Grad-CAM

## Future Work

  External validation on independent datasets
  Evaluation of newer architectures
  Quantitative validation of Grad-CAM explanations
  Model ensemble and uncertainty estimation
  
## Disclaimer

This project is intended for research and educational purposes and is not a substitute for professional medical diagnosis.
