# Machined Surface Inspection with Machine Learning

## Introduction
This repository contains the implementation and results of a study focused on the analysis of surface roughness characteristics in machined components using deep learning architectures. Our work utilizes Convolutional Neural Networks (CNNs) to analyze images of tactile plates machined with Electrical Discharge Machining (EDM), following VDI 3400 standards with 16 distinct surface roughness levels.

## Dataset Details
### Collecting Images
The images were captured using a Nikon Eclipse L150 Optical Microscope and a Sentech USB 2.0 Color Camera. The image analysis was performed with Clemex Vision PE software.

### Classification Details
Images are classified into 16 roughness categories, with each image having a resolution of 1600x1200 pixels.

## Models Used
We have used several state-of-the-art models for our study:
- VGGNet16
- ResNet50
- MobileNetV2
- DenseNet121
- YOLOv8

Each model has its own directory in the repository, where you can find the training scripts and the results.

## Getting Started
To run the models and replicate the study, follow these steps:

1. **Clone the Repository**
```bash
git clone https://github.com/amankhande/ME338.git
cd ME338
