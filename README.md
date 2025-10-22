# image-colorization
## Overview
This project demonstrates how to **colorize grayscale images** using a **Convolutional Neural Network (CNN)** trained on the **CIFAR-10 dataset**.
The model learns to predict the a and b color channels from the *L* (grayscale) channel in the CIELAB color space.

## Features
- Loads and preprocesses the CIFAR-10 dataset
- Converts RGB images to LAB color space
- Trains a CNN to predict color channels from grayscale inputs
- Visualizes colorization results using Matplotlib
- Saves the trained model for reuse

## Environment
This project was developed and trained in **Google Colab**, utilizing an **NVIDIA A100 GPU** to speed up training.
Make sure GPU acceleration is enabled in your Colab runtime for optimal performance.

## Dependencies
```bash
pip install tensorflow opencv-python matplotlib scikit-image Pillow numpy
```

## How to Run
1. Open the notebook in Google Colab
2. Make sure GPU runtime is enabled:
   **Runtime -> Change runtime type -> Hardware accelerator -> GPU**
3. Run all cells step-by-step
