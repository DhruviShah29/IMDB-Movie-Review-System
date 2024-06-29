# IMDB Movie Reviews Sentiment Classification

This repository contains a Python program for binary sentiment classification using the IMDB Movie Reviews dataset. The program uses deep learning techniques, specifically an LSTM neural network, to predict whether a movie review is positive or negative.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)
- [Prediction](#prediction)

## Introduction
The goal of this project is to build a deep learning model to classify IMDB movie reviews into positive and negative sentiments. We use the IMDB dataset, which contains 25,000 highly polar movie reviews for training and 25,000 for testing.

## Dataset
The IMDB dataset is provided by Keras and contains preprocessed movie reviews with words indexed by their frequency in the dataset. We use the top 10,000 most frequent words and pad sequences to a uniform length of 200 words.

## Requirements
To run this program, you need to have the following libraries installed:
- TensorFlow
- Keras
- NumPy
- Pandas

You can install the required libraries using pip:
```bash
pip install tensorflow keras numpy pandas
