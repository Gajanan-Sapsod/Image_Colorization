 # Image_Colorization_Project
 ## Table of Contents
* [Description](#Description "Goto Description")
* [Dataset](#Autoencoder "Goto Autoencoder ")
* [Model_Architecture](#Model_Archtecture "Goto Model Architecture")
* [Methods](#Methods "Goto Methods")
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
<img src="https://user-images.githubusercontent.com/105559761/201329358-8c388c61-ca1c-4d66-8c44-4d04f07723e1.png"  width="600" height="300">

## Hyperparameters
|Hyperparameter |Description|
|-----|--------|
| Optimiser|Adam Optimiser      |
|Learning rate  | 0.001      |
| Loss Function | MSE loss |
| Batch size | 256 |

# Results
<img src="https://user-images.githubusercontent.com/105559761/201330406-2c4b1c5c-d8e8-4fcc-b445-00d5ff3d2e3c.png" width="600" height="300">

<img src="https://user-images.githubusercontent.com/105559761/201337413-15cbb2e1-7d6b-4f63-9292-5e797bb35a9f.png" width="600" height="300" >                                                                                                                                        

                                                                                                                                          
