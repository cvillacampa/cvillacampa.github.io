---
title: "Input Dependent Sparse Gaussian Processes"
collection: publications
permalink: /publication/2021-input
excerpt: ''
date: 2021-10-18
venue: 'European Conference on Machine Learning and Knowledge Discovery in Databases'
paperurl: 'https://arxiv.org/pdf/2107.07281'
citation: 'Jafrasteh, B., & Villacampa-Calvo, C., & Hernández-Lobato, D.(2020). &quot;Input Dependent Sparse Gaussian Processes.&quot; <i>arXiv preprint</i>.'
---
Gaussian Processes (GPs) are Bayesian models that provide uncertainty estimates associated to the predictions made. They are also very flexible due to their non-parametric nature. Nevertheless, GPs suffer from poor scalability as the number of training instances N increases. More precisely, they have a cubic cost with respect to N. To overcome this problem, sparse GP approximations are often used, where a set of M≪N inducing points is introduced during training. The location of the inducing points is learned by considering them as parameters of an approximate posterior distribution q. Sparse GPs, combined with variational inference for inferring q, reduce the training cost of GPs to O(M3). Critically, the inducing points determine the flexibility of the model and they are often located in regions of the input space where the latent function changes. A limitation is, however, that for some learning tasks a large number of inducing points may be required to obtain a good prediction performance. To address this limitation, we propose here to amortize the computation of the inducing points locations, as well as the parameters of the variational posterior approximation q. For this, we use a neural network that receives the observed data as an input and outputs the inducing points locations and the parameters of q. We evaluate our method in several experiments, showing that it performs similar or better than other state-of-the-art sparse variational GP approaches. However, with our method the number of inducing points is reduced drastically due to their dependency on the input data. This makes our method scale to larger datasets and have faster training and prediction times. 

[Download paper here](https://arxiv.org/pdf/2107.07281)
