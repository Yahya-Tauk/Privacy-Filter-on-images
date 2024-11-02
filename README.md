# Face Privacy Filter

This project applies a privacy filter to faces in an image by detecting and blurring them. It uses `scikit-image` for face detection and image processing, and `matplotlib` for visualization.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

## Introduction
This project is designed to automatically detect faces in an image and apply a Gaussian blur to obscure them, preserving privacy. It uses pre-trained `Cascade` classifiers from `scikit-image` to locate faces and applies image processing techniques to blur the detected regions.

## Features
- Detects faces using a pre-trained face detection model.
- Applies a Gaussian blur to each detected face.
- Visualizes the original image and the privacy-filtered image side by side.

## Installation
To run this project, ensure you have Python installed along with the following libraries:
- `scikit-image`
- `matplotlib`
- `numpy`

### Install Dependencies
You can install the required packages using pip:
```bash
pip install scikit-image matplotlib numpy
