 # Image_Colorization_Project
 ## Table of Contents
* [Description](#Description "Goto Description")
* [Dataset](#Autoencoder "Goto Autoencoder ")
* [Model Architecture](#Model Archtecture "Goto Model Architecture")
* [Hyperparameters](#Hyperparameters "Goto Hyperparameters")
* [Results](#Results "Goto Results")
## Description
 The aim of this project is to colorize the given grayscale images .
## Dataset
 torch.torchvision.datasets.Flowers102 which consists of RGB images of various types of flowers.
## Model Architecture
* First six layers of Resnet pretrained network model as encoder
* Decoder of six layers to extract the information
## Hyperparameters
* Adam optimiser
* Learning rate 0.001
* Loss function MSE loss
* Batch size 256
# Results

