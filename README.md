# Detection of COVID-19 and Viral Pneumonia using Chest X-Rays

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
Image classification using Resnet18 to predict whether a person has COVID-19 or Viral Pneumonia based on their chest X-ray. The file __COVID-19 and Viral Pneumonia Detection using Chest X-Rays and Resnet18__ contains the notebook in which the Resnet18 model is first defined and then trained.

It goes into first creating the custom datasets. Separating them into a test and training set and transforming the image. Then we create a Data Loader and begin to create and train our model. Lastly, we observe our results by looking at how accurately we were able to make these predictions.

## Libraries used 
* Numpy
* os
* shutil
* PIL
* Matplotlib
* torchvision
* torch

```bash
%matplotlib inline

import os           # Used to access file system and create or rename directories
import shutil       # Used to manupilate file system and create a test folder
import random
import torch
import torchvision       # Torch vision library in order to transform our images and use the Resnet18 pretrained model
import numpy as np

from PIL import Image     # Pillow library in order to import the Image class and use instances to handle the images
from matplotlib import pyplot as plt
```

## Dataset used 
* __COVID-19 Radiography Database__ - Kaggle

## Built with
* Jupyter Notebook

## Ackowledgements
* <a href='https://www.kaggle.com/tawsifurrahman/covid19-radiography-database'>COVID-19 Radiograpghy Database</a> - Dataset
__M.E.H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M.A. Kadir, Z.B. Mahbub, K.R. Islam, M.S. Khan, A. Iqbal, N. Al-Emadi, M.B.I. Reaz, M. T. Islam, “Can AI help in screening Viral and COVID-19 pneumonia?” IEEE Access, Vol. 8, 2020, pp. 132665 - 132676.__

## Author - Sharan Sukesh



