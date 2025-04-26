Pre-trained Model (Transfer Learning)
This repository contains a detailed implementation of transfer learning using pre-trained deep learning models.
It aims to provide an intuitive understanding of how existing powerful models can be fine-tuned for new tasks.
The code uses Python and PyTorch (or TensorFlow, depending on your setup) while focusing on the key concepts behind transfer learning.

Features
Pre-trained Models: Usage of popular architectures like ResNet, VGG, etc.
Fine-tuning: Modify and retrain specific layers for a new dataset.
Efficient Training: Leverage learned features to achieve high accuracy with less data and time.
Visualization: Optional visualization of predictions and model behavior.
Requirements
To run the code in this project, you need:

Python 3.7+
PyTorch or TensorFlow (as used in the notebook)
NumPy
Matplotlib
Jupyter Notebook
Dataset
The dataset used in this notebook is: UEH-VDR (Vietnamese Dish Recognition Dataset)
https://www.kaggle.com/datasets/truthtaicom/uehvdr-dataset

Project Overview
The notebook includes:

Introduction to Transfer Learning: Brief explanation of the concept and when to use it.
Loading Pre-trained Models: How to load architectures like ResNet, VGG, etc.
Customizing the Model: Freezing/unfreezing layers and modifying output layers.
Training and Evaluation: Training the customized model on a new dataset and evaluating its performance.
Result Visualization: (Optional) Plotting predictions to visually inspect model accuracy.
