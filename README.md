**Skin Lesion Detection Using Deep Learning Models**

This repository contains a deep learning-based system for automated skin lesion classification utilizing the HAM10000 dermoscopic image dataset. The project is aimed at developing an accurate and robust multi-class classifier for seven types of skin lesions, supporting early detection and diagnosis of skin cancer.

*Project Overview*

The system encompasses all stages from data preprocessing to model training and evaluation:

Data Preparation: Includes loading and preprocessing images, handling class imbalance with targeted augmentation techniques, and splitting the data.

Model Architecture: Implements transfer learning using pre-trained architectures like ResNet50 fine-tuned for the HAM10000 dataset.

Performance: ResNet50 achieved an accuracy of 93.81% on the test dataset, demonstrating effective classification of seven common skin lesion types.

Visualization: Provides training/validation accuracy and loss plots, confusion matrix, and classification reports to analyze model performance comprehensively.
