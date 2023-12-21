
# Severity Detection of Diabetic Retinopathy using Deep Learning

The Goal is to develop a deep learning model that can detect the Severity of Diabetic Retinopathy in eyes using the fundus images.

## Introduction

we address the critical issue of Diabetic Retinopathy (DR), a leading cause of blindness in adults with diabetes. This condition, which damages the retina's blood vessels, often remains undetected until it reaches a severe stage. The goal is to develop a machine learning model that can automatically classify the severity of DR from retinal images, aiding in early detection and treatment.  advanced image processing techniques, such as the U-Net Model for lesion segmentation and Deep Learning for classification are used.

## Datasets

Messidor 1: The Dataset contains a total of 1200 retinal fundus images.  
Link: https://www.adcis.net/en/third-party/messidor/  
Messidor 2: The Dataset consists of a total of 1748 retinal images.                      
Link: https://www.adcis.net/en/third-party/messidor2/   
Aptos:  The Dataset consists of 3662 retinal images.                     
Link: https://www.kaggle.com/c/aptos2019-blindness-detection

## Methodology

Pre-Processing: Class balancing using Data Augmentation ( Over Sampling and Under Sampling),
Applying Guassian filter to highlight features.  

Models Used: CNN (own), Vision Transformers (ViT), ResNet, DenseNet, EfficientNetV2B0, InceptionV3.

## Results

### Messidor 1
Before Augmentation - Highest Accuracy: 50%, Best Model: Own CNN (model 6 ).  
After Augmentaion :-  
Over Sampling - Highest Accuracy: 52 %, Best Model: DenseNet  
Under Sampling - Highest Accuracy: 58%, Best Model: EfficientNetV2B0

### Messidor 2
Highest Accuracy: 78%, Best Model: EfficientNetV2B0 

### Aptos
Highest Accuracy: 95%, Best Model: EfficientNetV2B0

## Acknowledgement
Gratitute to Department of Computer Science at Sam Houston State University for their support and resources.


