# Pre-trained Model (Transfer Learning)

This repository provides a complete implementation of **transfer learning** using popular **pre-trained deep learning models**.  
It is designed to help you intuitively understand how powerful existing models can be fine-tuned to solve new problems efficiently.  
The code is written in **Python** using **PyTorch** (or **TensorFlow**, depending on your setup).

---

## Features

- **Pre-trained Models**: Usage of well-known architectures like **ResNet**, **VGG**, and others.
- **Fine-tuning**: Modify and retrain specific layers to adapt to a new dataset.
- **Efficient Training**: Leverage previously learned features to achieve high performance with less data and training time.
- **Visualization**: (Optional) Visualize predictions and model behavior for better understanding.

---

## Requirements

Make sure you have the following installed:

- Python 3.7+
- PyTorch or TensorFlow
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Dataset

The dataset used for training and evaluation:

UEH-VDR (Vietnamese Dish Recognition Dataset)
https://www.kaggle.com/datasets/truthtaicom/uehvdr-dataset

Make sure to download and extract the dataset into the appropriate folder as specified in the notebook.

---

## Project Overview
The notebook covers:
- Introduction to Transfer Learning: A brief explanation of the concept and typical use cases.
- Loading Pre-trained Models: How to load and configure models like ResNet, VGG, etc.
  
Customizing the Model:
- Freezing and unfreezing layers.
- Modifying output layers to match the number of classes in the new dataset.
  
Training and Evaluation:
- Training the modified model.
- Evaluating model performance using accuracy and loss metrics.
  
Result Visualization: (Optional)
- Plotting sample predictions.
- Analyzing model behavior visually.

---

## Results

Example output visuals and performance graphs are included in the notebook.
Training logs and saved models are stored under the /outputs directory.

