# Traffic Sign Classification

## Introduction

Classify traffic signs using traditional machine learning method and deep learning methods.

## Dataset

You can download the dataset from [Google Drive](https://drive.google.com/drive/folders/1vQubmgHQuVFoZ7JCpLwyG3PM16rHhjYU).


## Requirement

Task 1 requires

- numpy
- cv2
- tqdm
- scipy
- sklearn

Task 2 requires

- torch
- pytorch_lightning
- torchvision
- PIL
- tqdm

## Results

Achived 95.16% accuracy of task 1, and 97.89% accuracy of task 2 on the test set. Although I have relatively high accuracy of task 1, the accuracy of task 2 is not that high enough. The reason is that I adopted the network structure in this paper [[content](https://www.sciencedirect.com/science/article/abs/pii/S0893608018300054?via%3Dihub), [code (Lua)](https://github.com/aarcosg/tsr-torch)], but did not have time to shrink its size to fit our dataset (Our dataset is much smaller so this will apparently cause overfitting problems).
