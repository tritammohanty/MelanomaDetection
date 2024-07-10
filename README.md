# Melanoma Detection Assignment
> This project is aimed to build a multiclass classification model using a custom convolutional neural network in TensorFlow. The CNN based model should accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Poblem Statement: To build a CNN based model which can accurately detect melanoma. 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The data set contains the following diseases: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Built 11 models using different statergies to find out the best model to solve the problem statment.
- 11th model is deemed to be the best model.
- Scaling, Dropouts, Data Augmentation, Batch Normalization Statergies helped building a good model.
- Deeper network prformed better.
- More epoch increased the training and validation accuracy. But it inacrreased chances of overfitting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.26.4
- pandas - 2.2.2
- matplotlib - 3.7.5
- tensorflow - 2.15.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project took help from on [this tutorial](https://www.tensorflow.org/tutorials/images/classification).


## Contact
Created by [@tritammohanty] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->