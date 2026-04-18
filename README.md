# VITA-UNet

Official PyTorch implementation of **VITA-UNet** for medical image segmentation.

## Overview
This repository contains the implementation of **VITA-UNet: Volume and Uncertainty Informed Task-Adaptive U-Net**.

Current release includes:
- BraTS2020 training pipeline
- 3D VITA-UNet with deep supervision
- VPS (Volume-Penalized Segmentation) loss
- Region-based WT/TC/ET loss
- Sliding-window full-volume inference
- Test-time augmentation
- EMA, OneCycleLR, auto-resume, and checkpoint saving

BraTS2021 and ISLES2022 support will be added in subsequent updates.

## Features
- 3D multi-modal MRI segmentation
- BraTS-style 4-class prediction
- Dice + smoothed CE + VPS + region loss
- Full-volume evaluation with per-case metrics
- HD95, Dice, IoU summaries
- Training visualizations and logs

## Repository Structure
```text
VITA-UNet/
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
├── train_brats20.py
└── docs/
