# Interpretable & Pattern-aware Cloud Segmentation using Feature Semantic Learning

## Description:

This project tackles the crucial challenge of cloud detection in remote sensing imagery, enabling the effective utilization of vast Landsat satellite data archives. It proposes a novel deep convolutional neural network (DCNN) architecture, ED-CNN, for robust cloud and snow segmentation. ED-CNN leverages an enhanced encoder-decoder structure, incorporating atrous spatial pyramid pooling (ASPP) within the encoder and feature fusion from different encoder stages in the decoder. This design demonstrably improves segmentation accuracy and paves the way for transferable cloud detection methods using deep learning.

## Key Features:
* ED-CNN Architecture: A novel DCNN architecture designed specifically for cloud and snow segmentation in remote sensing images.
* Atrous Spatial Pyramid Pooling (ASPP): Enhances the encoder's ability to capture multi-scale features of clouds and snow.
* Feature Fusion Decoder: Improves segmentation accuracy by incorporating features from various encoder stages.
* Focus on Transferability: Explores the potential for deep learning models trained on similar sensors to be adapted for cloud detection on new satellites.
* Importance of Standardized Datasets: Highlights the significance of standardized datasets and benchmarking procedures for rigorous evaluation of cloud detection models.

## Getting Started:
1. Clone the Repository:
```git clone https://github.com/your-username/cloud-detection-ed-cnn.git```
2. Set Up Dependencies: 
```$ pip3 install -r requirements.txt```

## Results:
![graph1]results/1.jpeg
![graph2]results/2.jpeg
![graph3]results/3.jpeg
![graph4]results/4.jpeg

## Contributing:
We welcome contributions to this project! Feel free to open pull requests with bug fixes, improvements, or new features.
