<h1>
  EFFICIENTNET
</h1>
<p align="center">
  <a href="">
    <img src="https://1.bp.blogspot.com/-DjZT_TLYZok/XO3BYqpxCJI/AAAAAAAAEKM/BvV53klXaTUuQHCkOXZZGywRMdU9v9T_wCLcBGAs/s1600/image2.png" height="300px">
  </a>
</p>

&nbsp;

[![All Contributors](https://img.shields.io/badge/all_contributors-73-orange.svg?style=flat-square)](./CONTRIBUTORS.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)

## Table of Contents

- [Overview](#Overview)
- [Installation](#Installation)
- [Screenshots](#Screenshots)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Overview

Compound Model Scaling: A Better Way to Scale Up CNNs and EfficientNet
Traditional approaches to scaling Convolutional Neural Networks (CNNs) often focus on increasing one dimension at a time—depth, width, or image resolution. However, this can lead to suboptimal performance or inefficient use of resources. The Compound Model Scaling method, introduced with EfficientNet, offers a more balanced and principled approach.
Instead of scaling dimensions independently, Compound Scaling uses a compound coefficient to uniformly scale depth, width, and resolution using a fixed set of scaling constants. This method was derived through neural architecture search and enables the model to use parameters more efficiently, achieving higher accuracy with fewer FLOPs and parameters than previous CNNs.
EfficientNet, built on this scaling method, demonstrates state-of-the-art performance on image classification benchmarks while being significantly more lightweight than models like ResNet or Inception.
![CompoundModelScaling](https://1.bp.blogspot.com/-Cdtb97FtgdA/XO3BHsB7oEI/AAAAAAAAEKE/bmtkonwgs8cmWyI5esVo8wJPnhPLQ5bGQCLcBGAs/s1600/image4.png)

## Installation

Build Backpropagation from the source and install dependencies:

```bash
git clone https://github.com/hakuriver2002/EfficientNet.git
```

Navigate to the project directory:

```bash
cd EfficientNet
```

You need to install some library of tensorflow keras:

```bash
pip install tensorflow
```

```bash
pip install keras
```

## Screenshots
### Accuracy Value result
![Accuracy](https://github.com/user-attachments/assets/3d452a7f-d6b1-45de-b4b1-246090b7b3b7)

### Loss MSE result
![Loss](https://github.com/user-attachments/assets/6d8e8412-9c0e-4f43-bc0a-9d6ea0a3c514)


### Accuracy Value with EarlyStopping result
![AccuracyEarlyStopping](https://github.com/user-attachments/assets/c68802af-8385-4a9b-a14a-2a606c30335c)

### Loss MSE with EarlyStopping result
![LossEarlyStopping](https://github.com/user-attachments/assets/89b60f89-0974-423e-96b1-1211405c61e1)
