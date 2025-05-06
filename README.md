# NYCU CV 2025 Spring HW3

StudentID: 110550046  
Name: 吳孟謙

## Introduction

This is the implementation for Homework 3 of NYCU Computer Vision 2025 Spring, which focuses on **Instance Segmentation** of medical cell images.  
The model is based on `Mask R-CNN with ResNet50 + FPN` from torchvision's detection module, with custom data preprocessing and augmentation techniques.

## Method Summary

- **Model**: Mask R-CNN (`maskrcnn_resnet50_fpn_v2`)
- **Backbone**: ResNet-50 with Feature Pyramid Network
- **Data Augmentation**:
  - Horizontal & vertical flip
  - Brightness and contrast jittering
- **Loss**: Standard Mask R-CNN losses
- **Pretrained Weights**: ImageNet (via torchvision)

## How to install & run  

### dependencies  
just run the dependency installation cell(2nd cell) in the ipynb file  
or run this in terminal  
```bash
pip install torch torchvision numpy opencv-python tqdm Pillow pycocotools 
```
### Training
just run the training cell(3rd cell) in the ipynb file

### Inference
just run the inference cell(last cell) in the ipynb file

