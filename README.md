# PlantDiseaseDetection

## Overview
Creating a fast and cost effective way to identify plant diseases using Convolutional Neural Network. Two approaches are applied to address this problem. The first approach uses 5 layers convolutional neural network with Keras. The second approach applies ResNet 152 Deep Neural Network with PyTorch. 90% accuracy obtained

## Environment
Python version: 3.X

Develop platform: Google Colab

## Prerequisite
The libraries used include: nltk, sklearn, numpy, matplotlib.pyplot, pandas, spacy, seaborn.
Dataset: [PlantVillage Dataset](https://www.kaggle.com/emmarex/plantdisease)

## How to run
Both [Keras.ipynb](https://github.com/damien2012eng/PlantDiseaseDetection/blob/main/Keras.ipynb) and [Pytorch.ipynb](https://github.com/damien2012eng/PlantDiseaseDetection/blob/main/Pytorch.ipynb) were developed on Google Colab, so it is easy to open it through Colab and run the code cell sequently.

Keras:
Open the code file
Keras --- main.ipynb
Testing
Runtime --- Run all
Training (Optional):
Change `TRAIN` to True. --- Runtime --- Run all

Pytorch:
Open the code file
Pytorch--- main.ipynb
Testing
Runtime --- Run all
(Here you may encounter a couple of bugs
<br><br
1. Need to switch to GPU.
<br><br>
2, Import Error.
``` Python
   
    Cannot import name ‘isStringType’’
```
*The instruction listed on the next page

Training (Optional):
Change TRAIN to True. --- Runtime --- Run all --- Enter the authorization code with your UOttawa account




Instructions to fix the previous bugs
1. Need to switch to GPU.
Edit --- Notebook settings --- Hardware accelerator --- Select ‘GPU’ --- Save --- Runtime ---
Run all

2, Import Error. Cannot import name ``‘isStringType’``
Runtime --- Restart runtime --- Select Cell 2 --- Run after
