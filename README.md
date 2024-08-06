# Differential Cryptanalysis of SPECK 32/64 Cipher using Deep Learning

A comparitive analysis of ResNet and DenseNet architectures for analyzing the security of SPECK 32/64 lightweight block cipher through differential cryptanalysis. This repository holds data and code for the paper: "Comparative Analysis of ResNet and DenseNet for Differential Cryptanalysis of SPECK 32/64 Lightweight Block Cipher".
 [Paper link](https://link.springer.com/chapter/10.1007/978-981-97-0641-9_34)

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Code Structure](#code-structure)
- [Usage](#usage)





## Introduction

In this research project, we delve into the realm of differential cryptanalysis—a prominent method for assessing cryptographic algorithm security—and explore the effectiveness of modern deep learning architectures in this context. The focus of our investigation revolves around two widely recognized deep learning architectures: ResNet (Residual Neural Network) and DenseNet (Densely Connected Convolutional Network). Our objective is to comprehensively analyze their capabilities in deciphering the differential behaviour of the SPECK 32/64 lightweight block cipher.

Through a series of experiments and meticulous analysis, we ascertain the accuracy and efficiency of both ResNet and DenseNet architectures in decrypting the cipher's differential behavior. The outcomes of our research provide valuable insights into the comparative strengths of these architectures, shedding light on their potential applications in cryptographic analysis and algorithm security evaluation.


## Getting Started
The libraries used are interdependent, make sure to install all of them in your system,
before you begin, ensure you have the following prerequisites:

- Python (version 3.10.8)
- pip (Python package manager, version 22.3.1)

## Code Structure
- `ResNetModel.ipynb`: Contains the ResNet model implementations.
- `DenseNetModel.ipynb`: Contains the DenseNet model implementations.
- `speck.ipynb`: Includes the SPECK 32/64 cipher algorithm implementation.
- `ResDense.ipynb`: Scripts for visualizing results.

## Usage
To run the analysis using ResNet or Dense Net:

import the ResNet model `ResNetModel.ipynb` or the DenseNet model `DenseNetModel.ipynb` on google colab and upload the Speck file `speck.ipynb` locally.
Run the notebook individually to see the performance of the models.

To visualise and compare both of the model's performances, import `ResDense.ipynb` on google colab and upload the speck file `speck.ipynb` locally, Run this notebook for the visual
Comparison.

By default all of the code/implementations run for Round-5 Encryption (nr=5). To compare for higher rounds, increase the value of nr to 6,7,8 subsequently.
