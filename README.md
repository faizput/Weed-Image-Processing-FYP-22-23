# Weed-Image-Classification for Precision Agriculture (FYP-22-23)

## Overview
This includes the main code for my machine learning training and evaluation. The datasets used for the project were not provided in these repositories.

## Dataset
The dataset used in this project were sourced by my supervisor. The dataset contained images of broad-leaves and narrow-leaves weeds.

## Model
The project utilized transfer learning techniques by using structure and weights from 5 keras model pre-trained with the given dataset. The model used were VGG16, MobileNet V2, Xception, ResNet 50 V2 and Inception V3(2023). The project were then improved/modified in 2025 using only 3 which is VGG19, VGG16 and MobileNet V2 with some added evaluation metric.

## Evaluation Metrics & Prediction Preview
Below are few examples of metrics used to evaluete the model.

<img width="200" height="200" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/63fb88dd-10ae-4f0c-b029-fc856e0de8d3" />

<img width="200" height="200" alt="ROC Curve" src="https://github.com/user-attachments/assets/b76f404b-6f3d-45d0-aec3-86aa17b6c2f1" />

<img width="200" height="200" alt="Training   Validation Accuracy" src="https://github.com/user-attachments/assets/174c3ed3-f434-44f6-a868-3b53b03f6acb" />

<img width="200" height="200" alt="Image Prediction_Broad" src="https://github.com/user-attachments/assets/b38c2478-a5d1-4e2b-9158-988839b28c2f" />

<img width="200" height="200" alt="Grad-CAM Prediction" src="https://github.com/user-attachments/assets/92d07b21-23eb-4d38-b9ed-16f03200aae3" />
