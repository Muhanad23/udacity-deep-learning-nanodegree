# Udacity Deep Learning Nanodegree

This repository contains material related to Udacity's [Deep Learning Nanodegree program](https://www.udacity.com/course/deep-learning-nanodegree--nd101). It consists of a bunch of tutorial notebooks for various deep learning topics. In most cases, the notebooks lead you through implementing models such as convolutional networks, recurrent networks, and GANs. There are other topics covered such as weight initialization and batch normalization.

There are also notebooks used as projects for the Nanodegree program. The starting code is available here, as well as each project solution.

## Table Of Contents

### Tutorials

### Introduction to Neural Networks

* [Introduction to Neural Networks](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/intro-neural-networks): Learn how to implement gradient descent and apply it to predicting patterns in student admissions data.
* [Sentiment Analysis with NumPy](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/sentiment-analysis-network): [Andrew Trask](http://iamtrask.github.io/) leads you through building a sentiment analysis model, predicting if some text is positive or negative.
* [Introduction to PyTorch](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/intro-to-pytorch): Learn how to build neural networks in PyTorch and use pre-trained networks for state-of-the-art image classifiers.
* **[Project]** [Predicting Bike-Sharing Patterns](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/project-bikesharing): Implement a neural network in NumPy to predict bike rentals.

### Convolutional Neural Networks

* [Convolutional Neural Networks](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/convolutional-neural-networks): Visualize the output of layers that make up a CNN. Learn how to define and train a CNN for classifying [MNIST data](https://en.wikipedia.org/wiki/MNIST_database), a handwritten digit database that is notorious in the fields of machine and deep learning. Also, define and train a CNN for classifying images in the [CIFAR10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).
* [Transfer Learning](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/transfer-learning). In practice, most people don't train their own networks on huge datasets; they use **pre-trained** networks such as VGGnet. Here you'll use VGGnet to help classify images of flowers without training an end-to-end network from scratch.
* [Weight Initialization](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/weight-initialization): Explore how initializing network weights affects performance.
* [Autoencoders](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/autoencoder): Build models for image compression and de-noising, using feedforward and convolutional networks in PyTorch.
* [Style Transfer](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/style-transfer): Extract style and content features from images, using a pre-trained network. Implement style transfer according to the paper, [Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) by Gatys et. al. Define appropriate losses for iteratively creating a target, style-transferred image of your own design!
* **[Project]** [Dog Breed Classifier](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/project-dog-classification): Build a convolutional neural network with PyTorch to classify any image (even an image of a face) as a specific dog breed.

### Recurrent Neural Networks

* [Intro to Recurrent Networks (Time series & Character-level RNN)](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/recurrent-neural-networks): Recurrent neural networks are able to use information about the sequence of data, such as the sequence of characters in text; learn how to implement these in PyTorch for a variety of tasks.
* [Embeddings (Word2Vec)](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/word2vec-embeddings): Implement the Word2Vec model to find semantic representations of words for use in natural language processing.
* [Sentiment Analysis RNN](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/sentiment-rnn): Implement a recurrent neural network that can predict if the text of a moview review is positive or negative.
* [Attention](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/attention): Implement attention and apply it to annotation vectors.
* **[Project]** [TV Script Generation](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/project-tv-script-generation): Train a recurrent neural network to generate scripts in the style of dialogue from Seinfeld.

### Generative Adversarial Networks

* [Generative Adversarial Network on MNIST](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/gan-mnist): Train a simple generative adversarial network on the MNIST dataset.
* [Batch Normalization](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/batch-norm): Learn how to improve training rates and network stability with batch normalizations.
* [Deep Convolutional GAN (DCGAN)](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/dcgan-svhn): Implement a DCGAN to generate new images based on the Street View House Numbers (SVHN) dataset.
* [CycleGAN](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/cycle-gan): Implement a CycleGAN that is designed to learn from unpaired and unlabeled data; use trained generators to transform images from summer to winter and vice versa.
* **[Project]** [Face Generation](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/project-face-generation): Use a DCGAN on the CelebA dataset to generate images of new and realistic human faces.

### Deploying a Model (with AWS SageMaker)

* [Machine Learning Models Deployment](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/sagemaker-deployment): Learn to deploy pre-trained models using AWS SageMaker.
* **[Project]** [Sentiment Analysis Web App](https://github.com/muhanad23/udacity-deep-learning-nanodegree/tree/master/sagemaker-deployment/Project): Deploy an RNN performing sentiment analysis on movie reviews complete with publicly accessible API and a simple web page which interacts with the deployed endpoint.
