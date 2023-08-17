# Anomaly Detection on Washer Dataset

## Problem Statement
The goal of this project is to perform anomaly detection on a washer dataset using effective machine learning algorithms, with a focus on Variational AutoEncoder (VAE). The model is trained on the "washer_ok" dataset and then tested on the "washer_ng" dataset to predict and detect anomalies, visualized through generated heat maps.

## Overview
Anomaly detection is a fundamental task in the field of Computer Vision. In this project, we leverage the power of "Image Segmentation" techniques to detect anomalies within washer images. Four distinct algorithms have been employed for this purpose, each meticulously chosen after thorough dataset analysis and algorithmic research. The application of these algorithms on the dataset serves as a powerful means of uncovering anomalies.

## Dataset
The dataset comprises RGB images representing different instances of washers:
- `washer_ok`: 30 images
- `washer_ng`: 92 images

## Data Split
The data is divided into distinct sets for training, validation, and testing:
- Training Data: `washer_ok` (30 images)
- Validation Data: `washer_ng_kizu` (10 images)
- Test Data: `washer_ng_sabi` (4 images)

## Algorithms
The project employs the following cutting-edge algorithms to address the anomaly detection task:

1. **Variational AutoEncoder (VAE)**: The VAE algorithm showcases its ability to uncover latent patterns within the washer dataset.
2. **U-Net**: Leveraging the U-Net architecture, the model demonstrates its prowess in accurately segmenting washer images and highlighting anomalies.
3. **U-Net Xception Style**: This variant of the U-Net algorithm, inspired by Xception, enhances the anomaly detection capabilities.
4. **MultiResUnet**: The MultiResUnet algorithm further enriches the anomaly detection process with its multi-resolution approach.

## Reports

For a detailed exploration of the methodologies, results, and insights, please refer to the comprehensive report available in both English and Japanese versions.

This project exemplifies the synergy between sophisticated machine learning algorithms and domain-specific anomaly detection, showcasing its potential in real-world applications.
