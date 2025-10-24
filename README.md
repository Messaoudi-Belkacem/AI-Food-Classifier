# Food Image Classification with Transfer Learning (ResNet18)

This project demonstrates how to build and train an image classification model using transfer learning with a pre-trained ResNet18 on a custom food dataset. The goal is to classify images into different food categories.

## Table of Contents

1.  [Project Overview](#project-overview)
2.  [Dataset Structure](#dataset-structure)
3.  [Setup and Installation](#setup-and-installation)
4.  [Data Preparation](#data-preparation)
5.  [Model Building (Transfer Learning)](#model-building-transfer-learning)
6.  [Training](#training)
7.  [Evaluation](#evaluation)
8.  [Inference on Single Images](#inference-on-single-images)
9.  [Saving and Loading the Model](#saving-and-loading-the-model)
10. [Optional: Confusion Matrix and Grad-CAM](#optional-confusion-matrix-and-grad-cam)

## 1. Project Overview

This project covers the following steps:

- Preparing a custom food dataset with a specified folder structure.
- Loading and transforming image data using `torchvision.datasets.ImageFolder` and data augmentation.
- Utilizing transfer learning with a pre-trained `resnet18` model from `torchvision.models`.
- Training and validating the model.
- Saving the trained model.
- Performing inference on new images.
- Visualizing results with a confusion matrix.

## 2. Dataset Structure

The dataset should be organized into the following hierarchical structure: