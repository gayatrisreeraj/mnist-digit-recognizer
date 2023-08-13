# MNIST-digit-recognizer

# Overview: 

A machine learning project showcasing a Decision Tree-based approach to recognize handwritten digits from the renowned MNIST dataset. Through careful implementation and fine-tuning, this model achieves accurate digit classification, contributing to the advancement of image recognition techniques.

# Introduction

Welcome to the Handwritten Digit Recognition project. Our objective is to construct a machine learning model that can accurately identify hand-drawn digits ranging from zero to nine. The dataset is split into two files: "training dataset.csv" and "testing dataset.csv". Each image is comprised of 8 pixels in height and 8 pixels in width, making a total of 64 pixels per image. The pixel-values signify the lightness or darkness of each pixel, with higher values indicating darker shades. These pixel-values are integers ranging from 0 to 255.

# Dataset Overview:

Training Dataset ("training dataset.csv"): This dataset contains 66 columns. The first column serves as a unique identifier (ID) for each image. The second-to-last column represents the ground truth label, indicating the actual digit displayed in the image. The last column holds the category of the digit. The remaining columns contain the pixel-values of the associated image.

Testing Dataset ("testing dataset.csv"): The testing dataset is stored in a file with 65 columns. The first column represents the ID of each image. The subsequent columns hold the pixel values of the 8x8 (64 pixels) grayscale images.

# Objective:

Our primary aim is to build a machine learning model that can predict the correct digit label based on the pixel-values extracted from the hand-drawn images. The model's predictions will include both the ID and the category of the predicted digit.
