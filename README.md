# DOL-Project1
Implemented FedAvg &amp; FedProx:  Decentralized Optimization Algorithms for Neural Networks for an Image Classification Task


## Overview: 

In this project, we implemented federated learning algorithms as samples of the
decentralized optimization algorithms for the case when client datasets are i.i.d. or
non-iid. Then, compare the results with the centralized version.


For this purpose, a convolution neural network and the cifar10 dataset are used.
In the first part, we trained the network in a centralized manner, as in the standard
cases in deep learning. We implemented the FedAvg algorithm, one of the most
famous algorithms in federated learning, when the client datasets are iid. In the
following, the iid assumption was discarded. Thus, we split datasets in a non-iid
manner. Therefore for non-iid datasets, we implemented the FedProx algorithm
and compared the results to the FedAvg Algorithm.

