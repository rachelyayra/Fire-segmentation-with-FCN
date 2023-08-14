# Fire Semantic Segmentation

Welcome to the Fire Semantic Segmentation repository! This project focuses on utilizing Fully Convolutional Networks (FCNs) with varying depths (FCN-32, FCN-16, FCN-8) for the task of semantic segmentation of fire in images. The dataset used for training and evaluation was sourced from Kaggle, providing a diverse range of fire-related images for model development.

## Features

- **Semantic Segmentation**: The primary goal of this project is to accurately segment regions containing fire in images, enabling precise identification and localization of fire occurrences.

- **Multiple FCN Architectures**: This repository includes implementations of FCN-32, FCN-16, and FCN-8, allowing for experimentation with different network depths and levels of detail in segmentation.

- **Kaggle Dataset**: The dataset used for training and validation was collected from Kaggle, offering a comprehensive collection of images annotated with fire segmentation masks.

## Models

This repository contains the following FCN-based models for fire semantic segmentation:

1. **FCN-32**
   - Architecture: Fully Convolutional Network (FCN-32)
   - Description: The FCN-32 model provides a baseline for fire segmentation using a deep fully convolutional architecture. It offers a good balance between accuracy and computational efficiency.

2. **FCN-16**
   - Architecture: Fully Convolutional Network (FCN-16)
   - Description: The FCN-16 model enhances segmentation precision by incorporating skip connections from lower-level layers. This results in improved delineation of fire regions.

3. **FCN-8**
   - Architecture: Fully Convolutional Network (FCN-8)
   - Description: The FCN-8 model further refines segmentation accuracy by leveraging skip connections from multiple layers, leading to highly detailed fire region predictions.
