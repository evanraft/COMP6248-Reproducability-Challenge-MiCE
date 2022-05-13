# COMP6248 Reproducability Challenge, MiCE

We tried to reproduce the [paper](https://openreview.net/forum?id=gV3wdEOGy_V) "MICE: MIXTURE OF CONTRASTIVE EXPERTS FOR UNSUPERVISED IMAGE CLUSTERING". Using CIFAR-10 dataset we trained and testing two
different approaches, one baseline unsupervised model named moCo, and the Mixture of Contrastive Experts (MiCE). 

## train_MiCE.ipynb

The official code was used for reproducing the authors results. the train_MiCE file has the code for creating the model, the training and the evaluation on test
data

## moco_cifar10.ipynb

The code for training and testing the baseline MoCo model

## Results
Confusion Matrix of MiCE model in CIFAR-10 dataset

<img src="https://user-images.githubusercontent.com/44750127/168285157-da8d9d60-e799-4775-89ea-7e6c569869d7.png" width=40% height=40%>

Bar plot of predicted clusters of MiCE

<img src="https://user-images.githubusercontent.com/44750127/168285966-5e23ef2a-7248-4022-841e-f3aee55c62b8.png" width=40% height=40%>

