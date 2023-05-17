# Melanoma Detection Assignment

## Introduction
This assignment's purpose is to create a Convolutional Neural Network (CNN) model for reliable melanoma diagnosis. Melanoma is a kind of cancer that, if not diagnosed early, can be deadly. It is responsible for 75% of all skin cancer fatalities. We can possibly decrease the manual work necessary for diagnosis by developing a system that can analyse photos and warn dermatologists about the existence of melanoma.

## Dataset
This assignment's dataset contains 2357 photos of malignant and benign oncological illnesses. The photos were taken from the International Skin Imaging Collaboration (ISIC) and sorted using ISIC's categorization. Except for melanomas and moles, which contain a somewhat greater number of photos, the image subgroups were separated into equal numbers.

The dataset includes the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Technical Stacks
The following technologies were used in this assignment:
- PILLOW
- Augmentor
- numpy
- pandas
- seaborn
- tensorflow
- matplotlib
- tensorflow
- keras

## Model Creation
As part of this research, three models were created. The third model performed the best, obtaining reasonable accuracy on both the training and validation datasets. The Python script 'Vibhu_Dutt_Raturi_nn.ipynb' describes in detail how overfitting and class imbalance concerns were solved using augmentation techniques and the Augmentor module.


## Finally,
Finally, the constructed CNN-based algorithm showed potential for identifying melanoma properly. When compared to the other two models, the third model, which included augmentation techniques and the Augmentor library, performed better.

