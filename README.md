# fashion-mnist

## Purpose

This repo is a sandbox for testing different  machine learning algorithms

Currently this repo containes two Jupyter Notebooks, one for a neural net using tensorflow and keras and the other experimenting with kfolds using scikit-learn.

Jupyter Notebooks are web applications for creating and sharing computational documents in across multiple languages. Jupyter Notebooks are structured data that represent your code, metadata, content, and outputs. When saved to disk, the notebook uses the extension .ipynb, and uses a JSON structure. A big benefit to using Jupyter Notebooks is the ability to configure your runtime dependencies and environment.

I execute my notebooks in a linux environment on AWS Sagemaker but these notebooks can easily be ported to uses Google Colab as well.

## Dataset

The dataset used is the Fashion MNIST dataset

Recently, the researchers at Zalando, an e-commerce company, introduced Fashion MNIST as a drop-in replacement for the original MNIST dataset. Like MNIST, Fashion MNIST consists of a training set consisting of 60,000 examples belonging to 10 different classes and a test set of 10,000 examples. Each training example is a gray-scale image, 28x28 in size. The authors of the work further claim that the Fashion MNIST should actually replace MNIST dataset for benchmarking of new Machine Learning or Computer Vision models.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

The Labels are:
0 T-shirt/top 1 Trouser 2 Pullover 3 Dress 4 Coat 5 Sandal 6 Shirt 7 Sneaker 8 Bag 9 Ankle boot

Github link: https://github.com/zalandoresearch/fashion-mnist
