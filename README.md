# Surface-Defect-Detection-in-Ceramic-Tile-Manufacturing-using-computer-Vision
Defect detection is a critical process in ceramic tile manufacturing to ensure product quality and maintain efficient production control. Based on the severity of detected defects, appropriate corrective actions can be taken to minimize waste and improve overall productivity.

Manual inspection, once the industry standard, is labor-intensive, inconsistent, and prone to human error. To overcome these limitations, this project implements an automated defect detection system using deep learning and computer vision.
A deep learning-based approach is adopted using the EfficientNet-B0 architecture, which offers high performance with low computational cost.

Model Architecture

Backbone: EfficientNet-B0 (pre-trained on ImageNet)
Used as a feature extractor
Base model layers are frozen
A custom classification head is added
Custom Head:
Fully Connected (Linear) Layer
Sigmoid Activation Function
Outputs a probability score for binary classification (Defective / Non-Defective)
