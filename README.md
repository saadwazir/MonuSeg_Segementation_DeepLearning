```
This repo contains code from several github repos - Thankx to them :)

https://github.com/bonlime/keras-deeplab-v3-plus
https://github.com/hlamba28/UNET-TGS
https://github.com/dovahcrow/patchify.py
```

# Getting Started

This repo contains code to train and evaluate Unet and Deeplabv3Plus Neural Nets on MonuSeg Dataset to accomplish the segmentation task

## Dataset Preparation
```
Download MonuSeg Dataset
https://drive.google.com/open?id=1Bu0837C1v4ZIhWRG8zhBDPFuXzu1VN9Y

Generate patches of dataset to augmnet data offline
using patchify: https://github.com/saadwazir/Image_Patchyfy

or if you want to download the dataset in numpy arrays format with patches and 
load into program download npy files from here
https://drive.google.com/open?id=1oO4sGu6hI0woqOG4915X5lXCoHQBWqFp

```

## Trainig and Evaluation

```
------------ Unet ------------
open
unet-train-test.ipynb
from Unet folder to train and evaluate

Quantitative and Qualitative Results are in the notebook
```

```
--------- Deeplabv3plus ------
open
deeplabv3_train.ipynb
from deeplabv3plus folder to train

open
deeplabv3_test_evaluation.ipynb
to evaluate

Quantitative and Qualitative Results are in the notebook
```
