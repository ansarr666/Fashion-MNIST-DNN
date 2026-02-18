# Fashion-MNIST Classification using DNN (PyTorch)

This project trains a **Deep Neural Network (DNN / FFNN)** using **PyTorch** to classify clothing images from the **Fashion-MNIST** dataset.

## Dataset
- Fashion-MNIST (60,000 training + 10,000 testing images)
- 10 clothing classes
- Image size: **28×28 grayscale**

Classes:
- T-shirt/top, Trouser, Pullover, Dress, Coat  
- Sandal, Shirt, Sneaker, Bag, Ankle boot  

## Model (DNN)
The network is a fully connected deep neural net:
- Flatten layer (28×28 → 784)
- 3 hidden layers with ReLU
- Dropout for regularization
- Output layer with 10 logits (for 10 classes)

## Training Setup
- Loss: `CrossEntropyLoss`
- Optimizer: `Adam`
- Batch size: 128
- Epochs: 10
- Normalization applied to input images

## Results
Best performance achieved:

- **Test Accuracy: ~88.56%**
- Training Accuracy: ~89.96%

Sample training log:
