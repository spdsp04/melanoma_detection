# Melanoma Detection

![CNN](https://user-images.githubusercontent.com/93203186/166724500-4dd043cd-4357-48ed-9636-24cb44829e3c.jpg)

> This assignment is to build a multiclass classification model using a custom convolutional neural network in TensorFlow. To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

>The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the __International Skin Imaging Collaboration (ISIC)__. All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

## Project Pipeline

- __Data Reading/Data Understanding__ → Defining the path for train and test images 
- __Dataset Creation__ → Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
- __Dataset visualisation__  → Create a code to visualize one instance of all the nine classes present in the dataset 
- __Model Building & training :__
     - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
    - Choose an appropriate optimiser and loss function for model training
    - Train the model for ~20 epochs
    - Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.
- __Chose an appropriate data augmentation strategy to resolve underfitting/overfitting__
- __Model Building & training on the augmented data :__
    - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
    - Choose an appropriate optimiser and loss function for model training
    - Train the model for ~20 epochs
    - Write your findings after the model fit, see if the earlier issue is resolved or not?
- __Class distribution:__ Examine the current class distribution in the training dataset 
    - Which class has the least number of samples?
    - Which classes dominate the data in terms of the proportionate number of samples?
- __Handling class imbalances:__ Rectify class imbalances present in the training dataset with Augmentor library.
- __Model Building & training on the rectified class imbalance data :__
    - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
    - Choose an appropriate optimiser and loss function for model training
    - Train the model for ~30 epochs
    - Write your findings after the model fit, see if the issues are resolved or not?



* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).

## Contact
Created by __Durgesh Chaubey__
