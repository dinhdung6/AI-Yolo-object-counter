# Week 05 Portfolio Submission

This portfolio submission demonstrates how **CNN**, **ResNet50**, and **Mask R-CNN** are used to develop and evaluate deep learning models for **image classification** and **object recognition** tasks. The submission includes labeled datasets, model results, and organized source code.

## Contents

- **Labeled Dataset**  
  Ten images were annotated using the **LabelMe** program, and the associated JSON annotation file is included in the `labeled_log_dataset` folder.

- **CNN Model**  
  A basic Convolutional Neural Network (CNN) was trained to classify images as containing **rust** or **no rust**. Test images and classification results are located in the `cnn_test` folder.

- **ResNet50 Model**  
  The same rust classification task was performed using the **ResNet50** model. Test results are stored in the `resnet50_test` folder.

- **Mask R-CNN Model**  
  A **Mask R-CNN** model was developed to detect **log objects** in images. It outputs segmentation masks, bounding boxes, and confidence scores. All test results are stored in the `rcnn_test` folder.

- **Source Code**  
  All source code for the models and data processing scripts is located in the `code` folder.

## Overview

This project showcases how different convolutional neural network architectures perform on real-world image datasets for classification and object detection. It demonstrates dataset labeling, model training, testing, and result interpretation for practical deep learning tasks.

