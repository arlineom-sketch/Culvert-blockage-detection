# Culvert-blockage-detection
Computer vision methods for culvert blockage detection from CCTV imagery, including VLMs, DINOv3 and ResNet baselines with cross-site evaluation.
# Culvert Blockage Detection

Code accompanying the MSc dissertation *Image-Based Prediction of Culvert
Blockage from Urban Debris Events* at the University of Bath.

## Overview

This repository contains the code used to evaluate computer vision approaches
for detecting culvert blockage from CCTV imagery.

The experiments include:

- Vision-language model evaluation
- DINOv3 feature extraction and representation analysis
- DINOv3 + One-Class SVM anomaly detection
- DINOv3 + MLP supervised classification
- ResNet50 and ResNet34 reference baselines
- Cross-site evaluation on unseen monitoring sites

## Dataset

The experiments use the culvert CCTV dataset published by Vandaele (2023).
The original images are not redistributed in this repository.

## Repository Structure

Code is organised according to the experimental stages described in the
dissertation.

## Author

Arline Osorio Moreno  
MSc Artificial Intelligence in Engineering and Design  
University of Bath
