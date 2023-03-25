# CNN-Transfer-Learning-for-Sheep-Breed

This repository contains a single Jupyter notebook file that serves as a comprehensive guide on how to apply transfer learning concepts to classify sheep breeds from sheep face images using deep learning and computer vision techniques.

## Project Description
Sheep breeding is an important aspect of agriculture, and with the help of deep learning, it can be made easier and more efficient. In this project, we demonstrate how to use transfer learning to classify four different breeds of sheep based on their face images. This project is ideal for beginners who are interested in deep learning and computer vision and want to gain hands-on experience in applying these concepts.

## Techniques Used
The notebook covers two main techniques of transfer learning:

- Feature Extraction: This technique involves using a pre-trained model to extract relevant features from images, and then training a new classifier on top of those extracted features. This method is effective when dealing with limited training data.
- Fine-Tuning: This technique involves taking a pre-trained model and fine-tuning its weights on a new dataset. Fine-tuning can be more effective than feature extraction when the dataset is large.

## Sheep Breeds Dataset
The notebook classifies four different breeds of sheep, namely Marino, Poll Dorset, Suffolk and White Suffolk.
(Source : https://www.kaggle.com/datasets/divyansh22/sheep-breed-classification)

## Installation
The notebook can be accessed and run using Google Colab. Alternatively, if you prefer to run it locally, you will need to install the following libraries:

1. PyTorch: a powerful open-source machine learning library used for building deep neural networks.
2. Albumentations: a fast and flexible image augmentation library that can help you create better machine learning models.

## Conclusion & Preview

By utilizing transfer learning concept, high performance can be achieved without the needs of large dataset. Moreover, the performance can be further improved by fine-tuning the model. The evaluated performance can be stated with confusion matrix below : 

![image](https://user-images.githubusercontent.com/121663706/227727897-006d1cbe-4d7a-4fe8-b25c-8c3a3db68de9.png)

Here is a sample prediction of Poll Dorset sheep. It can be cleary seen that our CNN is able to predict the image of Pool Dorset sheep with high confidence value.

![image](https://user-images.githubusercontent.com/121663706/227727734-07117acc-49a6-4c0f-9555-f026efc118ad.png)
