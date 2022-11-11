 # Image_Colorization_Project
 ## Table of Contents
* [Description](#Description "Goto Description")
* [Dataset](#Autoencoder "Goto Autoencoder ")
* [Model_Architecture](#Model_Archtecture "Goto Model Architecture")
* [Methods](#Methods "Goto Methods)
* [Hyperparameters](#Hyperparameters "Goto Hyperparameters")
* [Results](#Results "Goto Results")
## Description
 The aim of this project is to colorize the given grayscale images .
## Dataset
 torch.torchvision.datasets.Flowers102 which consists of RGB images of various types of flowers.
## Model_Architecture
* First six layers of Resnet pretrained network model as encoder
* Decoder of six layers to extract the information
## Methods
![image](https://user-images.githubusercontent.com/105559761/201325391-d58ccc20-b279-49bd-be5f-5d0b11f94646.png)

## Hyperparameters
* Adam optimiser
* Learning rate 0.001
* Loss function MSE loss
* Batch size 256
# Results
![Screenshot (114)](https://user-images.githubusercontent.com/105559761/198292858-428aa7a1-2e3d-4bee-befa-3bc28709eb56.png )
![image](https://user-images.githubusercontent.com/107758088/198271333-aa99bc7c-37df-40f4-ada5-3b4156cd4e4d.png)
![image2](https://user-images.githubusercontent.com/107758088/198271032-39c9253f-9b55-42b0-aa94-904b19c4e622.png)
