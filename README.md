# Melanoma Detection Assignment
> This project focuses on detecting melanoma and other oncological skin diseases using a custom Convolutional Neural Network (CNN) model. 
The dataset used is from the International Skin Imaging Collaboration (ISIC),containing labeled images of various skin lesions. 
The project aims to build an image classification model to assist in early detection of skin cancer.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project involves developing a multiclass classification model to detect melanoma and other skin diseases.
The CNN model processes image data to predict the type of skin lesion from a set of nine possible classes.
- Early detection of melanoma is critical for improving patient outcomes.
Dermatologists rely on visual inspection and biopsy, but an automated system can assist in screening large volumes of patients, enabling faster diagnosis.
- The model aims to automate the detection of malignant skin lesions from images, reducing the manual effort and helping healthcare professionals in providing quicker diagnosis.
It can also improve accessibility to dermatological care in remote or under-resourced regions.
- The dataset used for this project is the ISIC Skin Cancer Dataset, containing labeled images of different types of skin lesions, categorized into multiple classes including melanoma, benign nevi, and other skin diseases.
The data was downloaded from Google Drive and augmented using Augmentor to handle class imbalance.


## Conclusions
- The CNN model initially showed signs of overfitting, where training accuracy continued to improve but validation accuracy started to drop.
After applying early stopping, the performance was stabilized.
- Data augmentation helped balance the class distribution, leading to improved model generalization.
- The model achieved satisfactory performance in detecting melanoma, but further tuning and hyperparameter optimization may improve accuracy.
- Using techniques like dropout and early stopping was essential to prevent overfitting and ensure the model could generalize well on the validation set.



## Technologies Used
- Python  - version 3.9
- TensorFlow - version 2.10
- Keras - version 2.10
- Augmentor - version 0.2.8
- Google Colab for model training and visualization


## Acknowledgements
- This project was inspired by the challenge of early melanoma detection, a critical task in medical image processing
- The dataset is provided by the ISIC.


## Contact
Created by Anushmita Mukherjee - feel free to contact me!
