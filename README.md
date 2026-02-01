# 🗑️ Garbage Image Classification Using CNN (PyTorch)
## dataset : https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset
## 📌 Project Overview

This project implements a **Garbage Image Classification System** using a **Convolutional Neural Network (CNN)** built from scratch with **PyTorch**.  
The system automatically classifies garbage images into different categories based on visual features learned from the data.

This project is developed for **academic and educational purposes**, such as coursework, thesis, and learning deep learning with PyTorch.

---

## 🎯 Objectives

- To build a CNN model for garbage image classification  
- To understand image feature extraction using convolutional layers  
- To train and evaluate a deep learning model using PyTorch  
- To apply deep learning techniques to environmental sustainability problems  

---

## 🧠 Model Architecture

The CNN model consists of the following components:

- **Convolutional Layers** – extract visual features from images  
- **ReLU Activation** – introduce non-linearity  
- **Max Pooling Layers** – reduce spatial dimensions  
- **Fully Connected Layers** – perform classification  
- **Output Layer** – predicts the garbage class  

The model is trained **from scratch** without using pre-trained networks.

---

## 🗂️ Dataset Structure

The dataset must be organized in a folder-based format:


Each folder name represents one garbage class.

---

## ⚙️ Technologies Used

- Python 3  
- PyTorch  
- Torchvision  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 🔄 Data Preprocessing

- Image resizing  
- Conversion to tensor  
- Dataset splitting into training and testing sets  

---

## 🚀 Training Process

The training process follows these steps:

1. Forward pass  
2. Loss calculation using **CrossEntropyLoss**  
3. Backpropagation  
4. Weight update using **Adam optimizer**  
5. Accuracy evaluation on test data  

---

## 📊 Evaluation Metric

- **Accuracy**

Accuracy is calculated as:

- Training Set = 87%
- Testing Set = 70%
