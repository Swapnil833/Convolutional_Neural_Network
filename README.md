# CNN Image Classification using CIFAR-10

## 📌 About the Project

This project implements a **Convolutional Neural Network (CNN) using PyTorch** to classify images from the CIFAR-10 dataset into 10 different categories. It covers data loading, CNN architecture design, model training using CrossEntropyLoss and the Adam optimizer, and performance evaluation.

## 🚀 Features

- **CIFAR-10 Dataset:** Load and process 60,000 color images across 10 classes.
- **CNN Architecture:** Build convolutional, activation, pooling, and fully connected layers.
- **Loss Function:** Use `CrossEntropyLoss` to calculate classification loss.
- **Optimization:** Train the network using the Adam optimizer.
- **Model Training:** Implement forward propagation, backpropagation, and parameter updates.
- **Model Evaluation:** Evaluate classification performance on the test dataset.

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib (optional, for visualization)

## 📂 Dataset

The CIFAR-10 dataset contains 60,000 RGB images of size 32 × 32 pixels, divided into 10 classes:

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

The dataset consists of 50,000 training images and 10,000 test images.

## 🧠 Model Workflow

1. Load the CIFAR-10 dataset using `torchvision.datasets.CIFAR10`.
2. Apply preprocessing and transformations to the images.
3. Build a CNN using convolutional, pooling, and fully connected layers.
4. Generate class predictions through forward propagation.
5. Calculate loss using `nn.CrossEntropyLoss()`.
6. Update model parameters using `torch.optim.Adam`.
7. Evaluate the trained model on the test dataset.

## ⚙️ Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd <repository-folder>
```

Install the dependencies:

```bash
pip install torch torchvision numpy matplotlib
```

## 📊 Model Evaluation

The trained CNN is evaluated on the 10,000-image CIFAR-10 test set. Evaluation can include:

- Test loss
- Classification accuracy
- Predicted versus actual class labels
