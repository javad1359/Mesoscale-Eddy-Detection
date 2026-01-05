

This repository contains an implementation of the paper  
**Mesoscale Eddy Detection and Classification From Sea Surface Temperature Maps With Deep Neural Networks**.

## 📄 Paper
- **Authors:** Javad Mahmoodi, Hossein Nezamabadi-pour
- **Journal:** IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing
- **DOI:**  https://doi.org/10.1109/JSTARS.2024.3402823
- 
## 📌 Overview
Oceanic mesoscale eddies play a key role in the transport of energy and chemicals in the ocean. This project presents EddyNet, a deep learning–based framework for the automatic detection and classification of ocean eddies using Sea Surface Temperature (SST) data from the Copernicus Marine and Environment Monitoring Service (CMEMS).

EddyNet is based on a U-Net–style encoder–decoder architecture with pixel-wise classification, producing segmentation maps where each pixel is labeled as non-eddy, anticyclonic, or cyclonic. The framework supports multiple CNN backbones (VGG, DenseNet, MobileNet) and is trained using Keras with the Adam optimizer and sparse categorical cross-entropy loss.

The proposed method achieves a good balance between segmentation accuracy and computational efficiency, making it suitable for real-time or large-scale oceanographic applications.
