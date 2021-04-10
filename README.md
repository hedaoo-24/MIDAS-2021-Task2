# MIDAS-2021-Task2

This repository contains ipynb files showing problem solving steps for a "Handwitten Character Recognition" problem. This was done in fulfillment of the MIDAS@IIITD Summer Internship/RA Task 2021.

## Part1

Use the given dataset to train a CNN. Pre-trained models are not allowed. Explain your design choices during preprocessing, model building and training. Also, cite the sources you used to borrow techniques. Save your model checkpoints. Testing data will be provided later.

## Part2

Train a network on only 0-9 images from dataset given for Part1. Use this pre-trained network to train on MNIST dataset. Use the standard MNIST train and test splits. How does this pretrained network perform in comparison to a randomly initialized network in terms of convergence time, final accuracy and other possible training quality metrics? Do a thorough analysis. Please save your model checkpoints.

## Part3

Train on given dataset for Part 3 using pre-trained network from Part2 and using scratch random initialisation. Provide test accuracy on the MNIST test set, using the same test split from part 2. Do the same analysis as 2 and report what happens this time. Try and do qualitative analysis of what's different in this dataset. Please save your model checkpoints.

## Notes :
 
To reproduce the virtual environment used, please run the command  
```
pip install -r requirements.txt
```
The `requirements.txt` file can be found in the repository.
