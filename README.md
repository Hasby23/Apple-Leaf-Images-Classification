# Apple Leaf Images Classification 

## Overview
Early identification of diseases affecting apple leaves is crucial for effective crop management. This research delves into the field of image classification for apple leaf diseases, using three different methodologies: Convolutional Neural Networks (CNN), pretrained CNN, and Support Vector Machines (SVM). Focusing on apple leaves and evaluating these three methods, the study aims to provide valuable insights into the most effective techniques for identification.

## Dataset
The dataset for this study was sourced from a publicly available repository on GitHub, comprising images of apple leaves. The images were collected from diverse orchards, ensuring a representative sample of leaves in various conditions. The dataset includes four main categories:
1. Apple Scab
2. Black Rot
3. Cedar Apple Rust
4. Healthy
The total number of images is 3171, for this study the dataset is split into train, validation, and test with a ratio of 80:10:10

Dataset source: https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color

## Models
Classification is performed using different methods. The first method employs Convolutional Neural Network, the second method utilizes a pretrained MobileNetV2 model, and the third method employs Support Vector Machine (SVM). For the first and second methods, Image Augmentation is conducted using ImageDataGenerator. In the third method, prior to SVM classification, feature extraction is performed using Principal Component Analysis (PCA).
