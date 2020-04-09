# Deep Learning: Virtual Adversarial Training

Author: Mohamed NIANG

A Regularization Method for Supervised and Semi-Supervised Learning

In this project, we are faced with a semi-supervised learning problem with MNIST data. The goal here is to make a prediction on MNIST data using only 100 labels. To do so, we use a regularization method based on the virtual loss of opponents: a new measure of the local uniformity of the conditional distribution of the input label. The virtual adversarial loss is defined as the robustness of the conditional distribution of the label around each input data point with respect to local perturbations. In contrast to contradictory training, this method defines the contradictory orientation without label information and is therefore applicable to semi-supervised learning.
