# Image Colorization Using Deep Convolutional Neural Networks

This project implements an **encoder-decoder convolutional neural network (CNN)** to perform **image colorization** and convert grayscale images into colorful RGB images.

It explores architectural choices and performance improvements.

- [About](#about)
- [Features](#features)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)

## About

Automatic image colorization is the task of predicting natural colors for grayscale images using a neural network. This project uses a **deep convolutional encoder-decoder architecture** to learn how to map grayscale pixel input to colorized outputs.

It's useful for:
- Restoring old grayscale images
- Enhancing visual data for computer vision tasks.
- Exploring deep learning architecture for image-to-image transformation.

The oxford flowers dataset, created by the Visual Geometry Group at the University of Oxford, was chosen over other ones. This dataset is a high-quality dataset containing photographs that have subtle categories which reinforces the colorizer model later on. It was primarily chosen due to its simplicity and consistent visual environment. As a result, this can offer better results.
Note: A more complicated dataset with different environments needs higher computational power and more time to run it over a lot of epochs.


## Features

- Trans a deep CNN to colorize grayscale images.
- Encoder-decoder architecture (with improvements such as skip connections)
- Perceptual Loss testing
- PatchGAN Discriminator
- Modular code (easy to modify and extend)

<img width="1336" height="787" alt="architecture image colorization" src="https://github.com/user-attachments/assets/9b18d43e-916b-4431-9bc1-c815d7684794" />


## Results
![efficientNet_combined](https://github.com/user-attachments/assets/1849a9f3-852c-4368-b350-98a638786fdd)

## Installation

Clone the repo:

```bash
git clone https://github.com/meddyahya/Image-Colorization-Using-Deep-Convolutional-Neural-Networks.git
cd Image-Colorization-Using-Deep-Convolutional-Neural-Networks
```

Install dependencies example:
```bash
pip install -r requirements.txt
```

