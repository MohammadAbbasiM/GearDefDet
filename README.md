# GearDefDet
A simple PyTorch-based project for detecting surface defects on industrial gears.
This work was part of my bachelor's project.

## Overview

This project uses a convolutional neural network (transfer learning on ResNet50), implemented in Python and PyTorch, to classify gear surface images into normal and defective categories.

The main code is provided in the Jupyter notebook:

```
Pytorch.ipynb
```

## Dataset

The dataset contains images of gear surfaces, collected by myself using a mobile phone and laptop.

**It includes:**
- Normal gears
- Defective gears (scratches, wear, etc.)

You can find a sample of the dataset in the dataset/ directory, and the complete dataset is available at:
[HuggingFace Dataset Link](https://huggingface.co/datasets/m-abbasi-m/Car-Gear-Surface-Defect-Detection).

This was my first experience using deep learning for a real-world problem, and also my first project uploaded to GitHub.

## Results

The model performed very well, achieving 100% accuracy on both the training and test datasets.
It also generalized successfully to unseen gear samples, correctly identifying defects on new parts.

<img src="https://github.com/MohammadAbbasiM/GearDefDet/blob/main/img/Picture2.png" width = 55% height = 55% div align=left />
<img src="https://github.com/MohammadAbbasiM/GearDefDet/blob/main/img/Picture1.png" width = 34% height = 34% div align=center />
