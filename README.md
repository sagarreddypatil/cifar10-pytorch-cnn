# CIFAR 10 CNN in PyTorch

## Performance
Test Accuracy: 87.31%
Train Accuracy: 99.92%

## How to run
`python main.py`

## Info
The model uses residual connections between the start and end of each Convolutional block. However, partial residual connections **have not** been implemented for blocks with different input and output size.

## Required Packages
 - pytorch
 - torchvision
 - tensorboard
 - scikit-learn
 - numpy
 - tqdm
