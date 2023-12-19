# breast-cancer-detection-CNN

Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. Accurately identifying and categorizing breast cancer subtypes is an important clinical task, and automated methods can be used to save time and reduce error.

 In this project, we tried to identify if the patient has IDC or not by using CNN.

We created a Tensorflow model that classifies breast tissue as containing Breast Cancer specifically Invasive Ductal Carcinoma (IDC) or not.

# Motivation
Enhancing Early Detection.

Technological Innovations.

Real-world Impact.

Empowering Healthcare Professionals.

# Data

We have 280 patients and roughly 280000 images. 

For each patient, we have an individual subfolder that contains image patches (patches of tissue slices).

# Model
The data is partitioned into Training, Development/Validation, and Test sets using distribution ratios of 0.75, 0.15, and 0.1, respectively. 

Our Convolutional Neural Network (CNN) architecture employs a series of convolutional blocks, each consisting of three consecutive 3x3 convolutional layers with increasing numbers of filters (32, 64, 128). 

The activation function for all layers, except the final dense layer, is Rectified Linear Unit (ReLU).

# Results
The model demonstrates robust performance, with both the validation and test sets achieving an accuracy within the range of 83%. 

It is important to highlight the emphasis on minimizing False Negatives over False Positives. The preference is to err on the side of caution, even if it results in a slight increase in False Positives, as False Negatives are considered more undesirable in medical diagnoses. The pursuit is for an optimal balance between recall and precision that aligns with acceptable trade-offs.
