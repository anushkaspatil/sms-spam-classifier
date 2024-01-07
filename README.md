# SMS Text Classifier

This project involves creating a machine learning model to classify SMS messages as either "ham" or "spam." A "ham" message is a normal message sent by a friend, while a "spam" message is an advertisement or a message sent by a company.

## Project Overview

The goal is to create a function named `predict_message` that takes a message string as an argument and returns a list. The first element in the list should be a number between zero and one, indicating the likelihood of "ham" (0) or "spam" (1). The second element in the list should be the word "ham" or "spam," depending on which is most likely.

## Dataset

The SMS Spam Collection dataset has been used for this project. The dataset is already divided into training and testing data.

- [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

## Project Structure

The project is organized into the following sections:

1. **Import Libraries and Load Data**: Import necessary libraries and load the training and testing datasets.

2. **Data Preprocessing and Model Training**: Preprocess the text data, train a Naive Bayes classifier, and evaluate the model on the validation set.

3. **Function for Message Prediction**: Create a function named `predict_message` that takes a message as input and predicts its likelihood of being "ham" or "spam."

4. **Test the Model**: Use the test set to evaluate the model's performance and print the test set accuracy.

## Acknowledgments
This project is based on a challenge of freecodecamp Machine Learning with Python course to classify the sms into ham or spam.

