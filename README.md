# CIFAR_Classification_CNN
Design a neural network model to classify CIFAR-10 Dataset from scratch
Background 


## CIFAR-10 Dataset: 
•	It consists of 60,000 colored images with 32 * 32 resolution
•	It has 50,000 train and 10,000 test
- Balanced Dataset

## Data Preprocess:
1.	Normalization: 
Data was normalized by standard normalization with 
mean = (0.4914, 0.4822, 0.4465) and std=(0.2470, 0.2435, 0.2616)

2.	Augmentation:
•	RandomHorizontalFlip
•	RandomRotation
•	brightness

4.	Resize:
Increase resolution to be (64 * 64)

## Hyperparameters:
•	Batch = 16 
•	Epochs = 70
•	LR = 0.001
•	Optimizer = Adam

## Model 
- Simple 4 convolutions layers , each 2 layers followed by max pooling inspired from VGG
- 2 fully connected layers

## Evaluations:
A) REQUIRED: 
1. Accuracy 
2. F1_score
3. Recall
4. Precision

B) Accuracy for each class

C) Confusion Matrix

D) Human Visualize test

## Problem of this model =)

Too sensitive for model complexty so It lead to not perfect performance

## upcomming aproaches

use ensampling technique : [here](https://paperswithcode.com/paper/an-image-is-worth-16x16-words-transformers-1)
