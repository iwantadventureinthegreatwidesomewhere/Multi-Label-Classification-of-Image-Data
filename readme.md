# Multi-label Classification of Image Data

We implemented a convolutional neural network (CNN) that identifies up to 5 digits in an image from a modified MNIST dataset. First, an algorithm was created that seperates all of the digits in an image using Canny Edge detection. Then, a CNN model was trained with the images of the isolated digits. The model consisted of 4 convolutions layers, each with a ReLU and max pool layer, that then gets flattened to 3 linear layers, finally reducing to a softmax output of 10 classes. Our model resulted in a test accuracy of 99.523% on over 14,000 images in a Kaggle competition.

<img src="competition.png" width="750">
