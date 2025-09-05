# MNIST-Handwritten-Digit-Classifier
This project implements a **Neural Network** using **TensorFlow/Keras** to classify handwritten digits (0–9) from the **MNIST dataset**.

# Files
- `MNIST_Digit_Classifier.ipynb` → Main Jupyter Notebook containing the implementation.

# Description
The project trains a simple feedforward neural network on the MNIST dataset.  
It includes:
- Data preprocessing (normalization and reshaping).
- Neural network model with two hidden layers (128 & 64 neurons).
- Training and validation with accuracy/loss visualization.
- Model evaluation on test data.
- Predictions on sample test images.

# Requirements
Install the following dependencies:
```bash
pip install tensorflow matplotlib numpy

#How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/MNIST-Digit-Classifier.git

Open the notebook:
bash
Copy code
jupyter notebook MNIST_Digit_Classifier.ipynb
Run all cells to train the model and visualize results.

#Results
Achieved ~97–98% accuracy on the test dataset.
Plotted training vs validation accuracy and loss.
Displayed predictions vs actual labels for sample images.

# Features
Beginner-friendly deep learning workflow.
Simple fully connected neural network (no CNN).
End-to-end training, evaluation, and visualization.
