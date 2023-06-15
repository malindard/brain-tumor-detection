# brain-tumor-detection

This project focuses on the detection of brain tumors using Convolutional Neural Networks (CNNs). Three different CNN models (ResNet50, InceptionV3, and VGG19) are implemented and compared using augmented and non-augmented datasets. The objective is to evaluate the impact of data augmentation on the performance of the models in brain tumor detection.

## Introduction
The detection of brain tumors plays a critical role in early diagnosis and treatment. This project aims to build an automated system that can effectively identify the presence of brain tumors in medical images using CNNs. Three different CNN models are implemented and evaluated to assess their capabilities in detecting brain tumors accurately.

## Dataset
The dataset used in this project consists of 253 images of brain MRI scans, comprising both tumor and non-tumor images. The dataset is appropriately divided into training and testing sets to ensure a balanced distribution of tumor and non-tumor images. The dataset is preprocessed and formatted to be compatible with the CNN models.
[Dataset from Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

## Models
Three CNN models are employed for brain tumor detection:
* ResNet50: This model utilizes the ResNet50 architecture as a feature extractor, followed by custom fully connected layers for classification.
* InceptionV3: Building upon ResNet50, this model incorporates the InceptionV3 architecture as a feature extractor, followed by custom fully connected layers for classification.
* VGG19: This model utilizes the VGG19 architecture as a feature extractor, followed by custom fully connected layers for classification.

## Result
The use of data augmentation has a significant impact on the performance of the CNN models for brain tumor detection. Models without data augmentation showed signs of overfitting, with higher training accuracy and lower validation accuracy and loss. On the other hand, models trained with augmented data exhibited improved results, with higher validation accuracy and lower validation loss. Augmentation helped the models learn patterns and variations in the dataset, enabling more accurate predictions on unseen data. Overall, all three CNN models demonstrated good performance in detecting brain tumors, showcasing their ability to process data effectively and generate accurate output.
