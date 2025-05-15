# Breast Cancer Classification and Segmentation using Multi-Task U-Net

This repository contains a custom implementation of a Multi-Task U-Net model designed for both segmentation and classification tasks. The model was trained and evaluated using the **Breast Cancer Ultrasound Image Dataset** to predict breast cancer categories and perform segmentation of ultrasound images.

## Features

- **Multi-Task Learning**: Combines segmentation and classification tasks into a single model.
- **Custom U-Net Architecture**: Modified U-Net to support dual-task outputs.
- **Breast Cancer Prediction**: Classifies ultrasound images into categories (e.g., benign, malignant, normal).
- **Segmentation**: Identifies and segments regions of interest in ultrasound images.

## Dataset

The model was trained on the **Breast Cancer Ultrasound Image Dataset**, which includes:

- Ultrasound images labeled with breast cancer categories.
- Ground truth masks for segmentation tasks.

You can find the dataset [here](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset).

## Model Architecture

The custom U-Net model consists of:

1. **Encoder**: Extracts features from input images.
2. **Decoder**: Reconstructs segmentation masks.
3. **Classification Head**: Predicts breast cancer categories from the encoded features.
