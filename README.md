# DL_Assignment

This repository contains the project of the course Deep Learning held by professor Elisa Ricci at University of Trento.

In this work, we implement the architecture and method formulated in the paper "Domain Attention Consistency for Multi-Source Domain Adaptation" [1] available at the following link: https://arxiv.org/abs/2111.03911. 

Moreover, to improve the performance of the model and obtain better adaptation results, we introduce a novel approach which takes advantage of a convolutional Discriminator with Gradient Reversal Layer (GRL) and features gradually modulated by the attention to promote the extraction of domain-invariant features, initially focusing on the global features and then, as the training proceeds, focusing on the features highlighted by the channel attention.
