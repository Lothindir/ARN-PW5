---
title: Learning with Artificial Neural Networks
subtitle: Practical Work 05 – Transfer learning
author: Francesco Monti
date: 13.05.2022
...

# Introduction

# Practical Work
## Model selection

At first we try some simple models with few added layers. For example those are the results of a model with a `Dropout` layer with a rate of 0.3 followed by a `Dense` layer with 16 neurons and 4 epochs. We can see that the performances are not really good:

![Simple model](docs/img/model1.png)

It is even worse if the complexity is too high. With two `Dense` layers, with 256 and 512 neurons each, in between two `Dropout` layers with rates of 0.3 and 0.2, we can observe that the loss is awful:

![Complex model](docs/img/model2.png)

