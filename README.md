# GAN for Handwritten Digits Generation

This repository contains an implementation of a Generative Adversarial Network (GAN) for generating handwritten digits similar to the MNIST dataset. The codebase is inspired by and adapted from [Sreenivas Bhattiprolu's GitHub repository]("https://github.com/bnsreenu/python_for_microscopists/blob/master/125_126_GAN_predict_mnist.py").

## Overview

Generative Adversarial Networks are a class of artificial intelligence algorithms used in unsupervised machine learning. This implementation focuses on generating realistic handwritten digits through the adversarial training of two neural networks, a generator, and a discriminator.

## Credits

The majority of the code in this repository has been referenced and adapted from [Sreenivas Bhattiprolu's GitHub repository]("https://github.com/bnsreenu/python_for_microscopists/blob/master/125_126_GAN_predict_mnist.py"). We acknowledge and appreciate their work in providing a foundation for this project.

Original repository: [Sreenivas Bhattiprolu's GitHub]("https://github.com/bnsreenu/python_for_microscopists")

## Requirements

To set up the environment for running this project, you can use the provided `requirements.txt` file. Create a virtual environment and install the dependencies using the following commands:

```
python -m venv venv
source venv/bin/activate  # For Linux/Mac
# OR
venv\Scripts\activate  # For Windows
pip install -r requirements.txt
```

## Execution

After setting up the environment, follow the steps below:

### 1. Training:

Run the following command in your terminal or command prompt to open the Jupyter Notebook for training:

```bash
jupyter notebook GAN_train.ipynb
```
### 2. Testing

Run the following command in your terminal or command prompt to open the Jupyter Notebook for training:

```bash
jupyter notebook GAN_test.ipynb
```