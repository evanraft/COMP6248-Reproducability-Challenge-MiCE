# COMP6248 Reproducability Challenge, MiCE

We attempted to reproduce the results from the [paper](https://openreview.net/forum?id=gV3wdEOGy_V) "MiCE: Mixture of Contrastive Experts for Unsupervised Image clustering". This is based on the unsupervised clustering algorithm MiCE, which uses the unsupervised deep learning algorithm techniques like contrastive learning and deep clusterin. Using the CIFAR-10 dataset, we trained and tested two different approaches, one unsupervised baseline model named moCo, and the MiCE. 
## train_MiCE.ipynb

The official code was used for reproducing the authors' results. the train_MiCE file has the code for creating the model, the training and the evaluation of test data

## moco_cifar10.ipynb

The code for training and testing the baseline MoCo model

## Results
Confusion Matrix of MiCE model in CIFAR-10 dataset. The accuracy reached 83%.

<img src="https://user-images.githubusercontent.com/44750127/168285157-da8d9d60-e799-4775-89ea-7e6c569869d7.png" width=40% height=40%>

Bar plot of predicted clusters of MiCE

<img src="https://user-images.githubusercontent.com/44750127/168285966-5e23ef2a-7248-4022-841e-f3aee55c62b8.png" width=40% height=40%>

