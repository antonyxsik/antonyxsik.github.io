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

Available for download on <a href="https://cran.r-project.org/web/packages/LatticeKrig/" target="_blank">CRAN</a>. When in R, just type `install.packages("LatticeKrig")` to download.

The `LatticeKrig` R package provides methods for efficiently interpolating massive spatial datasets using many basis functions and sparsity in key matrices. One of my recent projects focused on increasing the efficiency and accuracy of such methods, which led to my involvement in developing the new release of `LatticeKrig`. Many computational roadblocks have been removed in the current version, and a number of new methods and improvements have been added. Further updates will include experimentation with different basis functions, change of support, and data fusion capabilities!

<p align="center" style="margin: 20px 0;">
  <img src='/images/air_temp_LK.png' width='780'><br/>
</p>


Other Projects
======
Below are a few projects that have come from summer internships, trying to understand new concepts, or just having fun! 

- In order to better understand LLMs, specifically the transformer architecture, I built my own <a href="https://github.com/antonyxsik/ittybittyGPT" target="_blank">here</a>, and attempted to train it on the <a href="https://huggingface.co/datasets/roneneldan/TinyStories" target="_blank">TinyStories</a> dataset on my little GeForce RTX 3060 laptop GPU. This was done as a project for an exciting LLM interpretability <a href="https://github.com/mines-opt-ml/decoding-gpt" target="_blank">course</a> that I sat in on. 

- A quick tutorial on how to access versions of OpenAI's ChatGPT via the API to avoid the web version context window limits. I figured <a href="https://github.com/antonyxsik/GPT-API-Access-Tutorial" target="_blank">this repository</a> would be of practical use to my fellow graduate students, and others who may be interested. 

- During a summer at NASA JPL, I worked on using <a href="https://github.com/antonyxsik/Unsupervised_Anomaly_Detect" target="_blank">unsupervised anomaly detection</a> ML methods to detect failure modes of the Deep Space Network (DSN) antenna fleet. 

- In order to properly understand the fundamentals behind neural networks, I first built one from scratch in Numpy, then using PyTorch, and then in Flux.jl <a href="https://github.com/antonyxsik/NeuralNetExperiments" target="_blank">here</a>. 

For more fun projects like speeding up the R programming language using fast linear algebra primitives, experimenting with derivative free/zeroth order optimization methods, and even a template for this website, check out <a href="https://github.com/antonyxsik" target="_blank">my Github</a>! 
