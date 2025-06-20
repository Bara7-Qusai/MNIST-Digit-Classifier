# MNIST Digit Classifier with PyTorch

This project demonstrates a deep learning model built with PyTorch to classify handwritten digits from the MNIST dataset. It was developed as part of the AWS Machine Learning Fundamentals Nanodegree by Udacity.

### Overview
- **Dataset**: MNIST (28x28 grayscale images, digits 0–9)
- **Architecture**: Fully Connected Neural Network (3 hidden layers)
- **Preprocessing**: Normalization and conversion to tensors
- **Accuracy Achieved**: Up to **96.97%**
- **Framework**: PyTorch

### Features
- Data loading with `torchvision.datasets` and `DataLoader`
- Training and validation split (60% / 20% / 20%)
- Loss: `CrossEntropyLoss`, Optimizer: `SGD` with momentum
- GPU support for faster training
- Model saving with `torch.save()`

### Future Improvements
- Switch to Convolutional Neural Networks (CNN)
- Add live web demo using Flask or FastAPI

---
