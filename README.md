# HD-Machine-Learning-Capstone-Project

The aim of this Capstone project is to build a Recurrent Neural Network in Keras to perform sentiment analysis with the IMDB dataset. The  IMDB dataset is a common dataset for practise in Introductory Sentiment Analysis exercises and development.
The output of the model will be the classification of movie reviews into the catergories of either good (positive) or bad (negative).
The project was developed using the following steps: Get the dataset; Preprocessing the Data; Build the Model; Train the model; Test the Model and Prediction.

Numpy, matplotlib and tensorflow were the required packages for this python 3 task.

In the preprocessing stage the dataset is converted to an array and padded to a length of 500. The model has  4 layers; an embedding layer (to allow the neural network to work with text input as integers), a recursive LSTM layer and a regular LSTM layer and the Dense output layer.The model is then compiled and trained on the training data and validated on the testing data. Three epochs were enough to get reasonable results from the predictions on the model.
