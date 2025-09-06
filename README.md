[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronx378/Custom-MNIST-Classifier/blob/main/MNIST_Classifier.ipynb)

# Custom-MNIST-Classifier
Handwritten digit classifier using tensorflow. It uses a different activation function, extra layer, and visualizes the first 10 test predictions.

# Changes Made
- Two hidden layers: 128 (tanh) and 64 (relu) units
- Added Dropout (0.2) for regularization
- Increased epochs to 7, validation split of 10%
- Plots first 10 test image predictions for visual inspection

# How to Run
1. Install requirements:
       pip install tensorflow numpy matplotlib
2. Launch Jupyter notebook and run all cells.

# Example Output
- Accuracy after training: ~98%
- Visualizes the first 10 predictions, showing predicted and true labels.

# What I Learned/Changed
- **Experimented with tanh activation and extra layer which improved generalization slightly.**
- **Implemented dropout to reduce overfitting.**
- **Visualized predictions to validate errors.**
- Found setup and workflow easy; tuning and understanding validation took more time.

# Limitations
- Still relies on a simple feed-forward network.
- Did not tune hyperparameters extensively.


**Note:**  
This project demonstrates understanding of TensorFlow workflow, experimentation with architecture.