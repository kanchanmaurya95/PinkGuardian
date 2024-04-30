# Pink Guardian - Early Breast Cancer Detection App



Welcome to the **Pink Guardian** GitHub repository, where we integrate cutting-edge machine learning technology into mobile health applications to improve early breast cancer detection. This project showcases the development of the BC-InceptionV3 model, its training on Kaggle, conversion to TensorFlow Lite, and deployment in the Pink Guardian app.

## Table of Contents

- [Introduction](#introduction)
- [Project Description](#project-description)
- [Model Development](#model-development)
  - [Dataset Overview](#dataset-overview)
  - [Training on Kaggle](#training-on-kaggle)
  - [Conversion to TensorFlow Lite](#conversion-to-tensorflow-lite)
- [App Details](#app-details)
  - [Integration with Mobile App](#integration-with-mobile-app)
  - [Download the App](#download-the-app)
- [Results](#results)
- [Technical Information](#technical-information)
- [Citations](#citations)

## Introduction

Breast cancer remains a major global health challenge. Early detection significantly increases the chances of successful treatment. Pink Guardian utilizes advanced AI to provide accessible diagnostic tools directly through a mobile application, making early screenings more available and reducing barriers to access.

## Project Description

This project involves the creation of a comprehensive system that employs the BC-InceptionV3 model trained to classify mammogram images as benign or malignant. The model is trained in Python notebooks on Kaggle, converted to TensorFlow Lite, and then integrated into an Android app for easy user accessibility.

## Model Development

### Dataset Overview

The BC-InceptionV3 model is trained on high-quality mammographic images that provide a diverse basis for learning distinguishing features between benign and malignant tumors.

### Training on Kaggle

The model training is executed in a Python notebook hosted on Kaggle, leveraging its GPU resources to efficiently handle the computational demands of training a deep learning model.

### Conversion to TensorFlow Lite

Post-training, the model is converted to TensorFlow Lite to optimize performance for mobile devices, ensuring that the app runs smoothly across a wide range of smartphones.

## App Details

### Integration with Mobile App

The TensorFlow Lite model is integrated into the Pink Guardian mobile app, providing users with real-time analysis of mammogram images. This integration allows for immediate preliminary diagnostics to be made accessible on user's devices.

### Download the App

Scan the QR code below to download the **Pink Guardian** app directly to your device:


<img src="https://private-user-images.githubusercontent.com/26533517/326626110-fb8ed096-e201-4808-b57f-a4fac201e2c9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ0MzY4NjksIm5iZiI6MTcxNDQzNjU2OSwicGF0aCI6Ii8yNjUzMzUxNy8zMjY2MjYxMTAtZmI4ZWQwOTYtZTIwMS00ODA4LWI1N2YtYTRmYWMyMDFlMmM5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDMwVDAwMjI0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTkwMTgwMzM0NzEwZDdmMTFlMTIwYWNkODkxZWQ0YzIyMGQ0YmMzMjEwZWM0OTJhY2JmN2ExMTkxZjRiYjg3NzYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.NlUV-e3o6lgR7renFWr5uiy6wWiAQPN_CnqY0cMxgBI" alt="QR Code for Pink Guardian App" width="200"/>


## Results

The application of the BC-InceptionV3 model within the Pink Guardian app demonstrates high accuracy in detecting breast cancer signs from mammograms, providing a reliable tool for early detection.

## Technical Information

- **Programming Language**: Python
- **Technologies Used**: TensorFlow Lite, Kaggle, Android Studio
- **Model**: Custom BC-InceptionV3

## Citations

Relevant studies and references that have informed the development of the BC-InceptionV3 model and its implementation in Pink Guardian can be found here:

- [A curated mammography data set for use in computer-aided detection and diagnosis research](https://www.nature.com/articles/sdata2017177)
- [Kaggle for Data Science and Machine Learning](https://www.kaggle.com/)
- [TensorFlow Lite for Mobile Deployment](https://www.tensorflow.org/lite)

For more detailed references, please refer to the included citation file or section within the project documentation.
