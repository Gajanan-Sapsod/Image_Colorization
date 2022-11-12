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
* First six layers of Resnet-18-gray pretrained network model as encoder
* Decoder of six layers to extract the information
## Methods
<img src="https://user-images.githubusercontent.com/105559761/201329358-8c388c61-ca1c-4d66-8c44-4d04f07723e1.png"  width="600" height="300">

* Autoencoder: Autoencoder are used in this project.Autoencoder is a neural network which is composed of encoder,bottleneck and a decoder.

* Transfer Learning: Transfer learning is the reuse of a pre-trained model on a new problem. In transfer learning, a machine exploits the knowledge gained from a previous task to improve generalization about another.

* ResNet 18 Gray: Deep neural networks are hard to train as their depth increases. This increase in depth comes with many problems such as vanishing and exploding gradient descent . Residual Networks or ResNets are a solution to such problems. Resnet-18-Gray is used in this project which is a pretrained Convolutional neural network that is 18 layers deep,but only first 6 layers of this network are implemented.

* LAB Color Space:  LAB Color Space is used in this project as by separating out the lightness component, the neural network only has to learn the remaining two channels for colorization.

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

                                                                                                                                          
