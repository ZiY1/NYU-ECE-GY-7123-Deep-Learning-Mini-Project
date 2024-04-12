# NYU-ECE-GY-7123-Deep-Learning-Mini-Project
Modified Residual Network on CIFAR-10, done by Ziyi Huang (zh2931) and Shuning Li (sl10916)

## Overview
The repository contains two ```.ipynb``` files. They are:
- ```ModifiedResNet_CIFAR.ipynb```: The main notebook used to train the network, it will generate a checkpoint file ```ckpt.pth``` as the saved model;
- ```CIFAR10_Inference.ipynb```: The notebook used to run inference on the no_label test set downloaded from Kaggle with the saved model.

## PreRequisistes
The code can be run in Google Colab. The following packages are required: 
- torch
- torchsummary
- torchvision
- os
- argparse
- sys
- pickle
- numpy
- matplotlib.pyplot

## Report
Detailed description of the experiments can be found in ```Modified Residual Network for Image Classification.pdf``` also uploaded in this repository.

## Result
With the model and hyperparameters chosen as described in ```./checkpoint```
| Type    | Accuracy |
| ------- | -------  |
| Train   | 99.99%   |
| Test    | 95.18%   |
