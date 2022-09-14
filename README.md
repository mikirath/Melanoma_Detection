# Melanoma Cancer Detection
> This project is concerned with building a CNN model to detect Melanoma Cancer. We have built 3 models in this project. The first one is without applying any hyperparameter. In the second model we have tried to use Augmentation strategy to reduce overfitting issue of the previous model. The third model has addressed the class imbalance problem in the dataset by adding Augmenter library. The third model is a decent and generalisable model.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- We are trying to create a model that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- With proper Data Augmentation Strategy the problem of underfitting/overfitting can be handled to some extent.
- Addition of Augmentation library helped in reducing the problem of class imbalance.
- The Training and Validation Accuracy of the Model are 86% and 81% respectively.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow 
- matplotlib 
- numpy 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by the assignment provided by Upgrad.




## Contact
Created by [@mikirath] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->