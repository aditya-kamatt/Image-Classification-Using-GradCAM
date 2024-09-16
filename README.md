# Image Classification Using GradCAM
This repository contains code for image classification using GradCAM (Gradient-weighted Class Activation Mapping) to visualize the areas of an image that influence the predictions of a deep learning model. GradCAM is a technique to interpret and understand the decisions made by convolutional neural networks (CNNs).

## Overview
This project demonstrates how to apply GradCAM for visualizing the regions of an image that are significant for classification by a CNN. The primary components of this repository include:
- Image classification using a pre-trained CNN model.
- Implementation of the GradCAM algorithm.
- Visualization of class activation maps.
The goal of this project is to provide insights into how deep learning models make predictions and to enhance the interpretability of CNNs.

## Installation

To get started, you need to install the necessary dependencies. The project uses Python, and you can install the required packages using pip.

Clone the repository:
```bash
git clone https://github.com/aditya-kamatt/Image-Classification-Using-GradCAM.git
cd Image-Classification-Using-GradCAM
```

Install dependencies:
You can use a virtual environment to manage dependencies. For example:
```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
pip install -r requirements.txt
```
Alternatively, you can manually install the dependencies:
```bash
pip install numpy matplotlib tensorflow keras opencv-python
```
