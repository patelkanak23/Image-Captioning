# Image Captioning with Deep Learning

This project implements an image captioning model using deep learning techniques. It combines Convolutional Neural Networks (CNN) for feature extraction with Recurrent Neural Networks (RNN), specifically LSTM, for generating descriptive captions for images.

## Overview

The model uses the VGG16 architecture to extract features from images and employs an LSTM network to generate captions. It is trained on the [Flickr8k dataset](https://forms.illinois.edu/sec/1713398), which contains thousands of images with associated captions.

## Features

- Extracts image features using the VGG16 model.
- Cleans and preprocesses image captions.
- Uses LSTM for generating image captions.
- Evaluates the generated captions using BLEU scores.

## Dataset

Download the Flickr8k dataset and place it in the `Flicker8k_Dataset` directory.

## Usage

- Extract features from the images.
- Load and preprocess the captions from the dataset.
- Train the model on the preprocessed data.
- Generate captions for new images using the trained model.
- Evaluate the model's performance using BLEU scores.

## Evaluation

The model's performance can be assessed using BLEU scores to measure the quality of the generated captions against reference captions.

## Acknowledgements

- [Keras](https://keras.io/) for deep learning functionalities.
- [Flickr8k dataset](https://forms.illinois.edu/sec/1713398) for providing the dataset.
