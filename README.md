# Project Name
> ## Melanoma-Detection-Assignment

## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-information)
* [Project Pipeline](#project-pipeline)


Problem Statement - Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

General Info

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

    1. Actinic keratosis
    2. Basal cell carcinoma
    3. Dermatofibroma
    4. Melanoma
    5. Nevus
    6. Pigmented benign keratosis
    7. Seborrheic keratosis
    8. Squamous cell carcinoma
    9. Vascular lesion

Project Pipeline

    1. Data Reading/Data Understanding → Defining the path for train and test images 
    2. Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. 
    3. Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
    4. Model Building & training : 
        a. Create a CNN model, which can accurately detect 9 classes present in the dataset. 
        b. Choose an appropriate optimiser and loss function for model training
        c. Train the model for ~20 epochs
        d. Verify there is any evidence of model overfit or underfit.
        e. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
    5. Model Building & training on the augmented data :
        a. Create a CNN model, which can accurately detect 9 classes present in the dataset. 
        b. Choose an appropriate optimiser and loss function for model training
        c. Train the model for ~20 epochs
        d. Verify there is any evidence of model overfit or underfit.
    6. Class distribution: Examine the current class distribution in the training dataset 
    7. Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
    8. Model Building & training on the rectified class imbalance data :
        a. Create a CNN model, which can accurately detect 9 classes present in the dataset. 
        b. Choose an appropriate optimiser and loss function for model training
        c. Train the model for ~30 epochs
        d. Write findings after the model fit, see if the issues are resolved or not?
