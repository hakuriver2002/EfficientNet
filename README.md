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

Build EfficientNet from the source and install dependencies:

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
### Accuracy Value & Loss MSE result
![Accuracy-Loss-Epochs](https://github.com/user-attachments/assets/ca4c03d7-7c4b-446d-ab8d-6ee05c3a6d10)


### Classification report
![Classification-report](https://github.com/user-attachments/assets/55ea5ebe-354f-46a4-88ad-4c230cf45c2c)

### Matrix miss
![Matrix-miss](https://github.com/user-attachments/assets/1a9f2659-e830-4a62-84e4-1642e5ab6197)

### Images-true
![Images-true](https://github.com/user-attachments/assets/b061b094-12ab-42d6-ae17-3ebe46fe7231)

### Images-false
![Images-false](https://github.com/user-attachments/assets/3922293d-d248-4979-a5a1-f3450867d8c1)
