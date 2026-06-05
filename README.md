# Gait Recognition under Random Occlusion

Gait recognition is a biometric identification technique that recognizes individuals based on their walking patterns. Unlike traditional biometrics, it enables non-contact identification at a distance without requiring subject cooperation. However, real-world deployment remains challenging due to occlusions caused by objects, other individuals, or environmental structures, which can significantly degrade recognition performance.

This project implements **ODR-FEGR (Occlusion Data Reconstruction and Feature Extraction for Gait Recognition)**, a deep learning framework designed to improve gait recognition under occluded conditions.

### Architecture

The framework consists of two main modules:

* **Occlusion Data Reconstruction (ODR):** A 3D Convolutional GAN that reconstructs missing or corrupted regions in occluded gait silhouette sequences.
* **Feature Extraction for Gait Recognition (FEGR):** A dual-stream 3D/2D CNN architecture enhanced with **Global-Local Feature Extraction (GLFE)** blocks to learn discriminative gait representations from reconstructed sequences.

### Dataset

* Dataset: **CASIA-B**


### Objective

To enhance gait recognition accuracy in the presence of occlusions by combining silhouette reconstruction and robust feature extraction within a unified deep learning pipeline.
