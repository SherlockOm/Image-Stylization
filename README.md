# Image Stylization

Image Stylizatin is a deep learning project that allows you to merge the artistic style of one image with the content of another image. This repository provides a Python implementation of Image stylization using the TensorFlow framework.

![content image](https://github.com/SherlockOm/Image-Stylization/blob/main/output/output.png?raw=true)


## Overview

Image Stylization is a fascinating technique that combines the content of one image with the artistic style of another image. It uses convolutional neural networks to achieve this artistic transformation. This repository provides a user-friendly way to apply this technique to your own images using TensorFlow.

## Features

- Merge the style of one image with the content of another.
- Easy-to-use Python script with customizable parameters.
- Use pre-trained VGG-19 model for feature extraction.
- Save the stylized image to your local storage.

## Prerequisites

- Python 3
- TensorFlow
- Pillow
- NumPy

## Installation

You can install the required Python libraries using `pip`:

```bash
pip install tensorflow pillow numpy
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/neural-style-transfer.git
cd neural-style-transfer
```

Replace `content` image with the path to your content image and `style` image with the path to your style image. The stylized image will be saved in output folder.

2. Adjust the parameters in the script to fine-tune the style transfer process according to your preferences.

## Parameters

- `--content`: Path to the content image.
- `--style`: Path to the style image.
- `--output`: Path to save the stylized image.
- `--num_steps`: Number of optimization steps (default: 2501).
- `--style_weight`: Weight for the style loss (default: 1000000).
- `--content_weight`: Weight for the content loss (default: 1).
- `--learning_rate`: Learning rate for optimization (default: 0.01).


## Acknowledgments

This project is inspired by the work of Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. For more details, you can refer to their paper, ["A Neural Algorithm of Artistic Style"](https://arxiv.org/abs/1508.06576).

Feel free to contribute, report issues, and enhance the codebase. Enjoy creating your unique art with Image Stylization using TensorFlow!
