# MNIST Handwritten Digit Classification
This repository contains a project for classifying handwritten digits from the MNIST dataset using a deep learning model implemented in Keras. The project demonstrates data preprocessing, model building, training, and evaluation steps for a neural network.
# Project Structure
- Data Loading and Preprocessing: The MNIST dataset is loaded, and labels are explored to understand class distribution. Training and test images are visualized for better comprehension of the dataset.
- Data Normalization: The pixel values of the images are normalized to a range of [0, 1] to improve model performance.
- Model Training: The model is compiled with appropriate loss function and optimizer, then trained on the training data with validation.
- Model Evaluation: After training, the model is evaluated on the test data to measure its accuracy.
- Visualization: Sample images from the training data are displayed using Matplotlib to provide insights into the dataset.
# Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Keras
- Tensorflow
# Results
The trained model achieves high accuracy on the MNIST test set, demonstrating effective classification of handwritten digits. Visualization of sample images and their predictions is included to illustrate the model's performance.

# Acknowledgments
- The MNIST dataset, provided by Yann LeCun and Corinna Cortes.
- The Keras and TensorFlow teams for their powerful libraries.
