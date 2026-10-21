# Face Generation Using GANs and DCGANs

A Deep Learning project exploring **Generative Adversarial Networks (GANs)** to generate synthetic human face images using PyTorch and the CelebA dataset.

The project explores two approaches to image generation: a fully connected GAN and a Deep Convolutional Generative Adversarial Network (DCGAN). It covers image preprocessing, neural network design, adversarial training, loss functions, and visualization of generated images.

## Overview

Generative Adversarial Networks consist of two neural networks that compete against each other during training:

* **Generator:** Learns to generate synthetic images from random noise.
* **Discriminator:** Learns to distinguish real images from generated images.

Through adversarial training, the generator attempts to produce increasingly realistic images that can fool the discriminator.

This project explores the implementation of these concepts using PyTorch.

## Project Objectives

* Understand the fundamental concepts of GANs.
* Implement generator and discriminator networks using PyTorch.
* Load and preprocess human face images for training.
* Explore adversarial training and binary cross-entropy loss.
* Experiment with fully connected and convolutional GAN architectures.
* Generate and visualize synthetic face images.
* Develop practical experience with deep learning and computer vision.

## Technologies Used

* **Python** — Core programming language.
* **PyTorch** — Neural network implementation and training.
* **Torchvision** — Image transformations and visualization utilities.
* **NumPy** — Numerical operations.
* **Matplotlib** — Visualization of generated images.
* **Pillow (PIL)** — Image loading and processing.
* **tqdm** — Training progress utilities in the DCGAN notebook.
* **Google Colab / Jupyter Notebook** — Interactive development and experimentation.

## Dataset

This project uses the **CelebA (CelebFaces Attributes) dataset**, a large-scale dataset containing celebrity face images.

Dataset: CelebA

Official dataset website: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

The notebooks expect the image archive to be named:

`img_align_celeba.zip`

After extraction, the images are loaded from the `img_align_celeba` directory.
