---
layout: archive
title: "Software and Fun Projects"
permalink: /code/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

LatticeKrig R Package
======

One of my recent projects involved increasing the computational efficiency of basis function models for large spatial data sets. One deliverable from this project is software for reproducibility in the scientific community. Specifically, I am currently developing a new release of the `LatticeKrig` R package. 

The current binaries can be downloaded from [CRAN](https://cran.r-project.org/web/packages/LatticeKrig/). The package provides methods for interpolating big spatial data sets by using a large number of basis functions and efficient computation with clever use of sparsity. 

The development version can be downloaded from this [Github](https://github.com/antonyxsik/Normalization-Paper/tree/main), where a few significant computational roadblocks removed. Further updates will include experimentation with different basis functions and data fusion!


Other Projects
======
I also have a number of fun projects that have come from trying to understand new concepts, working different summer internships, or just having fun! A few are linked below. 

- During my time at NASA JPL, I worked on using [unsupervised anomaly detection](https://github.com/antonyxsik/Unsupervised_Anomaly_Detect) methods to detect failure modes of the Deep Space Network (DSN) antenna fleet. 

- In order to better understand LLMs, specifically the transformer architecture, I built my own [here](https://github.com/antonyxsik/ittybittyGPT), and attempted to train it on the [TinyStories](https://huggingface.co/datasets/roneneldan/TinyStories) dataset on my little GeForce RTX 3060 laptop GPU. This was done as a project for a brilliant mechanistic interpretability [course](https://github.com/antonyxsik/decoding-gpt) that I sat in on. 

- A quick tutorial on how to access versions of OpenAI's ChatGPT via the API to avoid the web version context window limits. I figured [this repository](https://github.com/antonyxsik/GPT-API-Access-Tutorial) would be of practical use to my fellow graduate students. 

- In order to properly understand neural networks, I first built one from scratch in Numpy, then using PyTorch, and then in Flux.jl [here](https://github.com/antonyxsik/NeuralNetExperiments). 

For more fun projects like speeding up the R programming language using fast linear algebra libraries, experimenting with derivative free/zeroth order optimization methods, and a template for this website, please check out [my Github](https://github.com/antonyxsik)! 