# MNIST Handwritten Digit Classification | CNN

A convolutional neural network (CNN) built with TensorFlow and Keras that recognises handwritten digits (0-9) from the MNIST dataset.

## What it does

- **Loads MNIST:** 60,000 training and 10,000 test images, each a 28×28 grayscale digit.
- **Prepares the data:** scales pixel values to 0-1, reshapes the images for the CNN and one-hot encodes the labels.
- **Builds the CNN:** two convolution and max-pooling blocks (32 and 16 filters), then a flatten layer, two dense layers (128 and 64 units) and a 10-class softmax output.
- **Trains and evaluates:** the model is trained with categorical cross-entropy loss and evaluated on the 10,000 test images, reaching a test loss of about 0.13.
- **Predicts:** generates class probabilities for every test image.

## Tech stack

Python, TensorFlow, Keras, NumPy, pandas, Matplotlib, Jupyter Notebook.

## Project structure

```
MNIST.ipynb    Data loading, preprocessing, CNN model, training and evaluation
```

## Author

**Amar Chaurasiya**: [LinkedIn](https://linkedin.com/in/amar-chaurasiya-163788262) · [GitHub](https://github.com/Amar1244) · amarchaurasiya124@gmail.com
