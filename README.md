# Image-Segmentation-for-Wildfire-Protection
Introduction

Wildfires have become increasingly frequent and severe due to climate change, posing significant risks to ecosystems, human life, and infrastructure. Accurately predicting how wildfires spread is essential for effective disaster management, resource allocation, and timely evacuation planning.

This project focuses on predicting next-day wildfire spread using deep learning-based image segmentation techniques. Given multi-dimensional spatial data representing environmental and geographical factors—such as temperature, wind, vegetation, elevation, and current fire masks—the goal is to generate a pixel-wise prediction map indicating the probability of fire spreading to each region.

To address this problem, we explore and compare multiple computer vision architectures, including Convolutional Autoencoders (CAE), U-Net, and Vision Transformers (SegFormer). These models are trained on a high-dimensional wildfire dataset to capture both local and global spatial patterns influencing fire behavior.

In addition to model performance, this project also emphasizes model interpretability, using techniques like saliency maps and Grad-CAM to identify which features contribute most to predictions. This helps in understanding the underlying factors driving wildfire spread and improving trust in model outputs.

Overall, this work highlights both the potential and challenges of applying deep learning to real-world environmental prediction tasks, particularly in handling complex spatial data and class imbalance.
