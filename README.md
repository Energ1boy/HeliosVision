# HeliosVision - CIFAR10 Image Recognition Model

HeliosVision is a simple AI image recognition model developed using a convolutional neural network (CNN) and trained on the CIFAR10 dataset. The model is implemented in a Jupyter Notebook and is capable of classifying images into one of 10 categories with a test accuracy of approximately 69.64%.

## Overview

HeliosVision can recognize images from the following 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Model Performance

The model achieves the following performance on the CIFAR10 test dataset:
Accuracy: 0.6964
Loss: 0.9187

## Features

- **Image Classification:** HeliosVision can classify images into one of the 10 CIFAR10 classes.
- **Simple CNN Architecture:** The model uses a straightforward convolutional neural network architecture.
- **Pre-trained Model:** The model is already trained and ready to use for inference.

## Limitations

- **Accuracy:** With an accuracy of 69.64%, HeliosVision may not be suitable for applications requiring high precision.
- **Generalization:** The model is trained specifically on the CIFAR10 dataset and may not perform well on images outside this dataset.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Energ1boy/HeliosVision.git
   cd HeliosVision

Open the Jupyter Notebook:
Start Jupyter Notebook and open HeliosVision_CIFAR10.ipynb.

Run the Notebook:
Execute the cells in the notebook to see the training process, evaluation, and predictions.

Requirements
Python 3.x
Jupyter Notebook
TensorFlow
Matplotlib
You can install the required packages using pip:
```bash
pip install tensorflow matplotlib
```
## Usage
**After running the notebook, you can use the model to make predictions on new images by adding the image to the notebook and running the prediction cells.**

