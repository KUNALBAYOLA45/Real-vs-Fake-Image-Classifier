# Real vs Fake Image Classifier

**Image Tampering Detection using ELA and CNN**

## Project Objective
The objective of this project is to combine the implementation of Error-Level Analysis (ELA) and Deep Learning to detect whether an image has undergone fabrication or editing, such as splicing. This tool helps to distinguish real images from tampered or manipulated ones using advanced image analysis techniques and Convolutional Neural Networks (CNN).

## Methods
Error-Level Analysis (ELA): Used to identify regions in an image with varying compression levels, indicating potential tampering.
Convolutional Neural Networks (CNN): Applied for image classification after processing the ELA-transformed images.

## Implementation Details

**Tech Stack:**
    TensorFlow,
    Keras,
    Numpy,
    OpenCV.
    
**Data Augmentation:** Used to artificially expand the dataset and improve model generalization.

## Pre-trained Models Used:

ResNet50,
VGG16,
VGG19.

## Results
Best Accuracy: Achieved a top accuracy of 91.83% during training .
