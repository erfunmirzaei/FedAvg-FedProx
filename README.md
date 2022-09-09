# DOL-Project1
Implemented FedAvg &amp; FedProx:  Decentralized Optimization Algorithms for Neural Networks for an Image Classification Task


## Overview: 

In this project, I implemented federated learning algorithms as one of decentralized optimization algorithms both for the case when client datasets are i.i.d. or non-iid. Then, compared the results with the centralized version.

For this purpose, I used a convolution neural network on the cifar10 dataset. In the first part, I trained the network in a centralized manner, as in normal case in deep learning, then I implemented FedAvg algorithm, which is the one of the most famous algorithms in federated learning, when the client datasets are iid. In the following, the iid assumption was discarded, thus I splitted datasets in a non-iid manner. Therefore for non-iid datasets, I implemented the FedProx algorithm, and compared the results to the FedAvg Algorithm.
