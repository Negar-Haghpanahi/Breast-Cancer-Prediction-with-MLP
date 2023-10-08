# Breast-Cancer-Prediction-with-MLP
*This is a collaborative project that I have done with two of my classmates for the data mining course.*
Introduction:
The primary objective of this project is to develop a model for the early detection of breast cancer. The dataset is divided into an 80-20 split for training and testing, respectively. Several preprocessing steps, such as normalization, are performed on the data. Feature selection is carried out using either correlation matrix or the Random Forest algorithm. The TensorFlow library is used for implementing the neural network model.

Neural Network Architecture:

The model architecture includes multiple hidden layers.
The number of neurons in each hidden layer is determined based on the problem's complexity.
Activation functions are used to introduce non-linearity into the model.
Overfitting Prevention:
To prevent overfitting, the model employs a validation split during training.
