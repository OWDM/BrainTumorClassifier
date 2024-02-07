# BrainTumorClassifier

A comprehensive toolkit for enhancing MRI images and classifying brain tumors using advanced image processing techniques and Convolutional Neural Networks (CNNs). Designed to tackle the complexities of MRI image analysis, this project aims at improving tumor detection accuracy with a specialized focus on small datasets.

## Introduction

Brain tumors present a significant challenge in medical imaging due to their varied appearance and the complex structure of the brain. The BrainTumorClassifier project addresses this challenge by providing tools for enhancing MRI images for better feature extraction and classification. This project leverages histogram equalization, thresholding, and CNNs to distinguish between tumor and non-tumor images effectively.

## Project Goals

The main goals of the BrainTumorClassifier are to:
- Enhance the contrast and features of MRI images using histogram equalization and thresholding techniques.
- Develop and train a Convolutional Neural Network (CNN) to classify MRI images into tumor or non-tumor categories.
- Address the challenges of working with a limited dataset of MRI images to improve model accuracy and generalization.

## Methodology

The project follows a structured approach to tackle brain tumor classification:

1. **Reading and Processing MRI Images**: Load and preprocess MRI images to prepare them for analysis.
2. **Histogram Equalization for Contrast Enhancement**: Apply histogram equalization to enhance the contrast of MRI images, making features more distinct.
3. **Thresholding for Feature Extraction**: Use thresholding techniques to highlight important features within the images.
4. **Developing and Training a CNN Model**: Design a CNN architecture and train the model on the preprocessed images for classification.

## Installation and Usage

Instructions for setting up the project and using the toolkit will go here. Include steps for installing dependencies, downloading the dataset, and running the main code.

## Dataset

This project uses a dataset of 248 MRI images available on Kaggle at [this link](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection). The dataset includes images classified as either having a tumor or not, presenting a unique challenge due to its limited size.

## Contributing

We welcome contributions to the BrainTumorClassifier project! If you're interested in helping, please take a look at our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to submit pull requests, report issues, or suggest enhancements.

