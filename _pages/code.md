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

The `LatticeKrig` R package provides methods for interpolating massive spatial datasets with many basis functions and efficient computation due to clever use of sparsity. The current binaries can be downloaded from <a href="https://cran.r-project.org/web/packages/LatticeKrig/" target="_blank">CRAN</a>.

One of my recent projects involved increasing the effiency and accuracy of such methods, along with providing software for reproducibility. As a result, I am currently developing a new release of `LatticeKrig`. The development version can be downloaded from this <a href="https://github.com/antonyxsik/Normalization-Paper/tree/main" target="_blank">repository</a>, where significant computational roadblocks have been removed. Further updates will include experimentation with different basis functions, change of support, and data fusion!

<p align="center" style="margin: 20px 0;">
  <img src='/images/air_temp_LK.png' width='800'><br/>
  <span style="font-size: smaller;"><strong>LatticeKrig at work:</strong> Interpolation performed when 80% of the observations are removed from a dataset that measures the air temperature in the contiguous US, resulting in something nearly identical to the original data. </span>
</p>


Other Projects
======
Below are a few projects that have come from trying to understand new concepts, working summer internships, or just having fun! 

- During my time at NASA JPL, I worked on using <a href="https://github.com/antonyxsik/Unsupervised_Anomaly_Detect" target="_blank">unsupervised anomaly detection</a> ML methods to detect failure modes of the Deep Space Network (DSN) antenna fleet. 

- In order to better understand LLMs, specifically the transformer architecture, I built my own <a href="https://github.com/antonyxsik/ittybittyGPT" target="_blank">here</a>, and attempted to train it on the <a href="https://huggingface.co/datasets/roneneldan/TinyStories" target="_blank">TinyStories</a> dataset on my little GeForce RTX 3060 laptop GPU. This was done as a project for an exciting LLM interpretability <a href="https://github.com/mines-opt-ml/decoding-gpt" target="_blank">course</a> that I sat in on. 

- A quick tutorial on how to access versions of OpenAI's ChatGPT via the API to avoid the web version context window limits. I figured <a href="https://github.com/antonyxsik/GPT-API-Access-Tutorial" target="_blank">this repository</a> would be of practical use to my fellow graduate students, and others who may be interested. 

- In order to properly understand the fundamentals behind neural networks, I first built one from scratch in Numpy, then using PyTorch, and then in Flux.jl <a href="https://github.com/antonyxsik/NeuralNetExperiments" target="_blank">here</a>. 

For more fun projects like speeding up the R programming language using fast linear algebra primitives, experimenting with derivative free/zeroth order optimization methods, and even a template for this website, check out <a href="https://github.com/antonyxsik" target="_blank">my Github</a>! 
