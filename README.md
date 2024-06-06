# Dog Breed Identification and Classification

## Overview

This project focuses on fine-tuning deep learning models for computer vision tasks, specifically identifying 120 different breeds of dogs using a subset of the ImageNet dataset. The dataset includes varying dimensions and higher resolutions than previous tasks, such as CIFAR-10. The model leverages transfer learning by using ResNet-18 for feature extraction and trains a custom output network to classify dog breeds accurately.

## Dataset

The dataset used for this project is available on Kaggle. It includes:
- Training set: 10,222 images
- Testing set: 10,357 images
- Labels for training data

The images are in JPEG format, contain RGB channels, and have varying dimensions. There are 120 different dog breeds in the dataset.

## Requirements
- Python 3.8 and above
- MXNet
- Gluon
- d2l
- Kaggle API
- Pytorch

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yeojustin/dog-breed-identification.git
   cd dog-breed-identification
