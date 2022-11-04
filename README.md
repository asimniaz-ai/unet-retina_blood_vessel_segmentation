# Retina Blood Vessel Segmentation using U-Net with PyTorch

This repository contains code for the Retina Blood Vessel Segmentation using U-Net with PyTorch on the DRIVE 2004 dataset.

#### NVIDIA 2080
#### CUDA 11.3
#### Python 3.7
#### PyTorch (conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch)

#### [DRIVE 2004](https://www.kaggle.com/datasets/zionfuo/drive2004)
The Drive 2004 dataset contains Digital Retinal Images for Vessel Extractions. For training and testing it has 20 images each. 
Therefore, we need to apply data augmentation on training images to increase the size of our training dataset.


#### Download the dataset and paste in the same folder as your code is in. Update the data path in train and test files accordingly.
