# MNIST Handwritten Digit Classification using CNN

This project uses a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The goal is to train the model to recognize digits from 0 to 9 using TensorFlow and Keras.


## Dataset

The MNIST dataset contains 60,000 training images and 10,000 testing images of handwritten digits, each of size 28x28 pixels in grayscale. These images are preprocessed by normalizing the pixel values to a range of 0 to 1 and reshaping them to include a channel dimension.


## Model Overview

The model is built using the following layers:
- **Convolutional Layers**: For feature extraction.
- **Pooling Layers**: For downsampling feature maps.
- **Fully Connected Layers**: For classification.
- **Dropout Layers**: To prevent overfitting.

The architecture includes techniques like Batch Normalization, ReLU activation, and both MaxPooling and AveragePooling.


## Training

The model is compiled using:
- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy
- **Metrics**: Accuracy  

It is trained for 100 epochs with a batch size of 256, and validation is performed on the test dataset.


## Results

The training and validation accuracy are plotted to visualize performance over epochs. The model achieves high accuracy in recognizing handwritten digits.


## Dependencies

- Python 3.8+
- TensorFlow 2.0+
- Keras
- Matplotlib





