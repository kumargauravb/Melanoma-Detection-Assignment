# Melanoma Skin Cancer Detection
> In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Algorithms Used
Convolutional Neural Network
### Dataset Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
### Steps Involved
- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model

## Conclusions
As the accuracy of the model increases, the loss decreases. The model is able to predict the class of the lesion with a high accuracy. Augmenting the data and countering class imbalance helped in improving the accuracy of the model.


## Technologies Used
- Python - version 3.8.10
- Tensorflow - version  2.13.0
- Keras - version 2.13.1
- Augmentor - version  0.2.12
- Matplotlib - version 3.7.1
- NumPy - version 1.24.3

## Acknowledgements
- This project was inspired by Upgrad Programme for ML and AI.

## Contact
Created by [@kumargauravb] - feel free to contact me!
