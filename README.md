# object-recognition

A convolutional neural network (CNN)  is deployed for object recognition. I have used the All-CNN network published in the 2015 ICLR paper,[ "Striving For Simplicity: The All Convolutional Net"](https://arxiv.org/pdf/1412.6806.pdf)

This convolutional neural network obtained state-of-the-art performance at object recognition on the CIFAR-10 image dataset in 2015. I have build this model using Keras, a high-level neural network application programming interface (API) that supports both Theano and Tensorflow backends.

Following tasks are accomplished:
  * Importing datasets from Keras
  * Using one-hot vectors for categorical labels
  * Adding layers to a Keras model
  * Loading pre-trained weights
  * Making predictions using a trained Keras model

The dataset used is the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
