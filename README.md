# IMDB Movie Review Sentiment Analysis using Simple RNN

This project implements a sentiment analysis model for IMDB movie reviews using a Simple Recurrent Neural Network (RNN). The model is trained to classify movie reviews as either positive or negative.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Scripts](#scripts)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Web Application](#web-application)

## Project Structure

The project consists of three main scripts:

1. `embedding.ipynb`: Demonstrates word embedding techniques.
2. `featureEngineering_and_model_training.ipynb`: Handles data preprocessing, feature engineering, and model training.
3. `prediction.ipynb`: Contains functions for making predictions using the trained model.
4. `app.py`: Streamlit app

Additionally, there's a Streamlit web application for easy interaction with the model.

## Scripts

### 1. embedding.ipynb

This script showcases various word embedding techniques:
- One-hot encoding
- Pad sequences
- Word embedding using Keras Embedding layer

### 2. featureEngineering_and_model_training.ipynb

This notebook covers:
- Loading and preprocessing the IMDB dataset
- Building and training a Simple RNN model
- Implementing early stopping
- Saving the trained model

### 3. prediction.ipynb

This script includes functions for:
- Loading the trained model
- Decoding reviews
- Preprocessing user inputs
- Making sentiment predictions

## Installation

To run this project, you need to have Python installed along with the following libraries installed :
clone the repository: 
```
git clone https://github.com/kshitijkumrawat20/ImdbMovieReviewSentimentAnalysisUsingRNN.git
```

```
pip install -r requirements.txt
```

## Usage

1. Run the `featureEngineering_and_model_training.ipynb` notebook to train the model and save it as 'rnn_model.h5'.
2. Use the `prediction.ipynb` notebook to make predictions on new reviews.

## Web Application

A Streamlit web application is available for easy interaction with the model. To run the app:

1. Ensure you have Streamlit installed: `pip install streamlit`
2. Run the command: `streamlit run app.py` (replace 'app.py' with the name of your Streamlit script)

The web app allows users to input a movie review and get a sentiment prediction (positive or negative) along with a prediction score.

```
