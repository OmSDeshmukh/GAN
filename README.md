# GAN for Handwritten Digits Generation

This repository contains an implementation of a Generative Adversarial Network (GAN) for generating handwritten digits similar to the MNIST dataset. The codebase is inspired by and adapted from [Sreenivas Bhattiprolu's GitHub repository](link-to-the-repo).




## Overview

Generative Adversarial Networks are a class of artificial intelligence algorithms used in unsupervised machine learning. This implementation focuses on generating realistic handwritten digits through the adversarial training of two neural networks, a generator, and a discriminator.

## Credits

The majority of the code in this repository has been referenced and adapted from [Sreenivas Bhattiprolu's GitHub repository](link-to-the-repo). We acknowledge and appreciate their work in providing a foundation for this project.

Original repository: [Sreenivas Bhattiprolu's GitHub](link-to-the-repo)

## Requirements

To set up the environment for running this project, you can use the provided `requirements.txt` file. Create a virtual environment and install the dependencies using the following commands:

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
# OR
venv\Scripts\activate  # For Windows
pip install -r requirements.txt

## Execution

After setting up the environment, run the blocks in GAN_train.ipynb file to train the model

For testing, run the GAN_test.ipynb with the correct model name input