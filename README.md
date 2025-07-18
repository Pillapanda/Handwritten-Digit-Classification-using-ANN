# Handwritten-Digit-Classification-using-ANN
This project performs handwritten digit recognition on the MNIST dataset using an Artificial Neural Network (ANN).
It classifies grayscale images of handwritten digits (0–9) into their respective categories.

One particularly useful insight was working with the MNIST dataset, which is already included in Keras — making it easy to access without the need to manually upload or download the data. You can load the dataset directly in your code with the following command:

(X_train, y_train), (X_test, y_test) = keras.datasets.mnist.load_data()

📝 Project Highlights
Built a deep learning model using Keras/TensorFlow.
Utilized the popular MNIST dataset, which contains 70,000 images of handwritten digits (28×28 pixels).
Designed an Artificial Neural Network (ANN) with fully connected layers.
Achieved an accuracy of approximately 97% on the test dataset.
Includes preprocessing steps like normalization and one-hot encoding of labels.

📁 Contents
mnist_ann.ipynb — Jupyter notebook with full code: data loading, preprocessing, model building, training, and evaluation.

🚀 Technologies Used
Python,
Keras & TensorFlow,
NumPy,
Matplotlib (for visualization)

📊 Results
✅ Accuracy on test data: ~97%,
✅ Demonstrates the effectiveness of deep learning on image classification tasks even with a simple ANN.
