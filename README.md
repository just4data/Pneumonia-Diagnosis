# Deep Learning for Automatic Pneumonia Detection
Detecting Pneumonia in Chest X-ray Images using Convolutional Neural Network


The pneumonia detection is usually performed through examine of chest X-ray radiograph by specialists. This process is tedious and often leads to a disagreement between radiologists. This repo builds and trains a convolution neural network to predict whether an X-ray scan shows presence of pneumonia. 

# Challenge:

Build an algorithm to automatically identify whether a patient is suffering from pneumonia or not by looking at chest X-ray images. Below is an example images which are included in the source dataset to train the machine learning model:

![alt tag](https://github.com/just4data/Pneumonia-Diagnosis/blob/main/examples.png)

The normal chest x-ray does not show any cloudiness or opaque places. On the other hand, the pneumonia scan shows unclear, opaque and cloudy areas. The dataset can be downloaded from the kaggle website which can be found [here](kaggle.com/paultimothymooney/chest-xray-pneumonia).

The below snippet plot shows the loss and accuracy data on the training and validation datasets over training epochs:

![alt tag](https://github.com/just4data/Pneumonia-Diagnosis/blob/main/loss%20and%20accuracy%20curve.png)
