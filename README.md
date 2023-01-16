# Pix2Pix-GAN
## Description
---
In this, we will implement an image-to-image translation method, based on
[pix2pix](https://phillipi.github.io/pix2pix/). To be more specific,  we'll built from scratch a GAN which can translate abstract labels into facade images. 

Before we start, please read the [pix2pix paper](https://arxiv.org/pdf/1611.07004.pdf) first and understand how pix2pix works.
### Part 1 Load dataset
---

We'll train a model to generate pictures of facades from label maps, using the [CMP Facade Database](http://cmp.felk.cvut.cz/~tylecr1/facade/) .

### Part 2 Models

* Implement a U-Net Encoder-Decoder Generator
* Implement a discriminator

### Part 3 Optimizor
---
For optimization, we'll use the Adam optimizer.

### Part 4 Training
See the notebook.

### Part 4 Evaluation
* Quantitative 
* Qualitative

### Part 5 Spectral Normalization