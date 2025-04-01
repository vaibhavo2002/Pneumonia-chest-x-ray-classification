# Pneumonia Chest X-ray Classification

## Overview
This project focuses on classifying chest X-ray images to detect pneumonia using deep learning. It utilizes a convolutional neural network (CNN) based on the VGG16 model for feature extraction and classification.

## Dataset
The dataset consists of chest X-ray images categorized into two classes:
- **Normal** (Healthy lungs)
- **Pneumonia** (Lungs affected by pneumonia)

## Model Architecture
The model is built using the **VGG16** architecture with the following modifications:
- Feature extraction from VGG16 pre-trained weights
- Fully connected layers with dropout for regularization
- Optimized using **Adam optimizer**

## Training Process
- Image data augmentation using `ImageDataGenerator`
- Early stopping to prevent overfitting
- Training and validation split for performance evaluation

## Performance Metrics
- **Training Accuracy:** 89.02%
- **Test Accuracy:** 91.51%
- **Loss:** 0.3608

## Algorithms Used
- **VGG16** (Pre-trained CNN for feature extraction and classification)

## Results
The model achieves high accuracy in detecting pneumonia, with performance improvements using data augmentation and transfer learning.

## Future Improvements
- Experimenting with different architectures (ResNet, EfficientNet)
- Hyperparameter tuning for better accuracy
- Deploying as a web-based diagnostic tool

## License
This project is licensed under the MIT License.

