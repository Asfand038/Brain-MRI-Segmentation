# Brain Tumor Segmentation Using U-Net

This repository contains the implementation of a deep learning model using the U-Net architecture for brain tumor segmentation from MRI scans. The project focuses on segmenting tumor regions from multi-class medical images.

## Project Overview

Brain tumor segmentation is a critical task in medical imaging that aids in precise diagnosis and treatment planning. In this project, a U-Net-based model is developed to automate the segmentation of brain tumors from MRI images. The model is trained using Keras and TensorFlow, optimized with binary cross-entropy loss and the Adam optimizer.

## Features

- **U-Net Architecture**: Designed for medical image segmentation, specifically brain tumor segmentation.
- **Data Preprocessing**: Handled with Keras ImageDataGenerator, OpenCV, and Numpy to manage multi-class masks.
- **Optimization**: Binary cross-entropy loss and Adam optimizer for efficient training.
- **Performance Evaluation**: Measured using Intersection over Union (IoU), dice score, and baseline mask comparisons.

## Technologies Used

- Python
- Keras
- TensorFlow
- OpenCV
- Numpy
