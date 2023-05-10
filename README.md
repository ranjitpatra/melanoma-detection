# Melanoma Detection
> Build a Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

> Dataset - https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view

## Technologies Used
- Google Collab + jupyter Notebook
- python - version 3.9.1
- numpy - version 1.23.4
- matplotlib - version 3.6.2
- keras - version 2.12.0
- tensorflow - version 2.12.0

## Conclusions

- Model 1 (Base Model) - Is overfit.
- Model 2 (with data augmentation + dropouts) - Resolves overfitting issue but observed as underfit.
- Model 3 (Fixed Class Imbalance by adding 500 images to each class using Augmentor + BN + 30 epochs - Class Rebalance helped to increase the Train and Validation accuracy.

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad and IIIT Bangalore.
- Upgrad course learning content, live session and Google search.


## Contact
Created by [[@ranjitpatra](https://github.com/ranjitpatra)] - feel free to contact!