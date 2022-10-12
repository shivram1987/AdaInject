# AdaInject Optimizer (IEEE Transactions on Artificial Intelligence)

This repository contains the code of AdaInject optimizer.

The paper is available on IEEE at: https://ieeexplore.ieee.org/document/9896941

The PDF is available on arXiv at: https://arxiv.org/pdf/2109.12504.pdf

## Abstract

The convolutional neural networks (CNNs) are generally trained using stochastic gradient descent (SGD) based optimization techniques. The existing SGD optimizers generally suffer with the overshooting of the  minimum and oscillation near minimum. In this paper, we propose a new approach, hereafter referred as AdaInject, for the gradient descent optimizers by injecting the second order moment into the first order moment. Specifically, the short-term change in parameter is used as a weight to inject the second order moment in the update rule. The AdaInject optimizer controls the parameter update, avoids the overshooting of the minimum and reduces the oscillation near minimum. The proposed approach is generic in nature and can be integrated with any existing SGD optimizer. The effectiveness of the AdaInject optimizer is explained intuitively as well as through some toy examples. We also show the convergence property of the proposed injection based optimizer. Further, we depict the efficacy of the AdaInject approach through extensive experiments in conjunction with the state-of-the-art optimizers, namely AdamInject, diffGradInject, RadamInject, and AdaBeliefInject on four benchmark datasets. Different CNN models are used in the experiments. A highest improvement in the top-1 classification error rate of $16.54\%$ is observed using diffGradInject optimizer with ResNeXt29 model over the CIFAR10 dataset. Overall, we observe very promising performance improvement of existing optimizers with the proposed AdaInject approach.

## Citation

If you use this code in your research, then please cite the following paper: Shiv Ram Dubey, S.H. Shabbeer Basha, Satish Kumar Singh, and Bidyut Baran Chaudhuri, AdaInject: Injection Based Adaptive Gradient Descent Optimizers for Convolutional Neural Networks, IEEE Transactions on Artificial Intelligence (TAI), Sept 2022.

@article{dubey2022adainject,
title={AdaInject: Injection Based Adaptive Gradient Descent Optimizers for Convolutional Neural Networks},
author={Dubey, Shiv Ram and Basha, S.H. Shabbeer and Singh, Satish Kumar and Chaudhuri, Bidyut Baran},
journal={IEEE Transactions on Artificial Intelligence (TAI)},
year={2022}
}
