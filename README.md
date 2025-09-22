# Digit-Recognition
This project demonstrates a beginner-friendly yet powerful implementation of an Artificial Neural Network (ANN) using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.
🔍 Overview
- Dataset: MNIST — 70,000 grayscale images of handwritten digits (0–9), each sized 28x28 pixels.
- Model Architecture:
- Input layer: 784 neurons (flattened 28x28 image)
- Hidden layers: 128 and 64 neurons with ReLU activation
- Output layer: 10 neurons with softmax activation (for 10 digit classes)
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam
- Metrics: Accuracy
🛠️ Key Features
- Data preprocessing with normalization and reshaping
- Model training with validation split
- Evaluation on test data with accuracy reporting
- Clean and modular code structure for easy understanding and extension
📈 Results
Achieved high accuracy on the test set after just 5 epochs of training, demonstrating the effectiveness of a simple ANN for image classification tasks.
🚀 Future Enhancements
- Integrate dropout layers to reduce overfitting
- Add early stopping and model checkpointing
- Visualize predictions and confusion matrix
- Experiment with Convolutional Neural Networks (CNNs) for improved performance
📚 Technologies Used
- Python
- TensorFlow & Keras
- NumPy
- Matplotlib (optional for visualization)
