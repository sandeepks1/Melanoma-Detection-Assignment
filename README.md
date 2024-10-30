# Skin Cancer Detection using CNN
> This project aims to develop a Convolutional Neural Network (CNN) model that can detect melanoma from images. Melanoma is a deadly form of skin cancer if not detected early. The model helps in automating the diagnosis process, reducing the effort needed by dermatologists.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project focuses on developing a machine learning model that can classify skin cancer images.
- Melanoma, a type of skin cancer, accounts for 75% of skin cancer-related deaths. Early detection can significantly improve patient outcomes.
- The model uses a custom Convolutional Neural Network (CNN) to classify images into various categories based on skin disease.
- The dataset consists of 2357 images sourced from the International Skin Imaging Collaboration (ISIC), covering nine different categories of skin diseases:
  1. Actinic Keratosis
  2. Basal Cell Carcinoma
  3. Dermatofibroma
  4. Melanoma
  5. Nevus
  6. Pigmented Benign Keratosis
  7. Seborrheic Keratosis
  8. Squamous Cell Carcinoma
  9. Vascular Lesion

## Conclusions
- The model was able to achieve a validation accuracy of ~55%, indicating a need for further improvement.
- Augmentation and transfer learning could further improve the accuracy.
- Class imbalance was handled using the Augmentor library and class weights.
- Further work includes fine-tuning the model for better generalization and accuracy.

## Technologies Used
- TensorFlow - version 2.6
- Keras - version 2.6
- Python - version 3.8
- NumPy - version 1.19.5
- Matplotlib - version 3.4.3
- Scikit-learn - version 0.24

## Acknowledgements
- This project was inspired by the need for automated early detection of melanoma to support dermatologists.
- The dataset was sourced from the International Skin Imaging Collaboration (ISIC).
- Special thanks to upGrad for educational resources and guidance throughout this project.

## Contact
Created by [@sandeepks1](https://github.com/sandeepks1) - feel free to reach out for any questions or collaborations!

