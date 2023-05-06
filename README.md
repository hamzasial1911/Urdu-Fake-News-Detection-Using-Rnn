# Urdu-Fake-News-Detection-Using-Rnn
This project is aimed at building a model for detecting fake news in the Urdu language using Recurrent Neural Networks (RNNs). The model will be trained on a dataset of labeled news articles, with the goal of accurately classifying new articles as either real or fake.

## Dataset
Before training our model, we have needed to preprocess the dataset. This will involve cleaning and tokenizing the text, removing stopwords, and converting the text into numerical data that can be input into our RNN

## Preprocessing
I have used a Recurrent Neural Network (RNN) for this project. Specifically, we will use a Long Short-Term Memory (LSTM) RNN, which is well-suited for processing sequential data. The architecture will consist of an embedding layer, one or more LSTM layers, and a dense output layer.


## Training
We have trained our model using the training set, using a combination of backpropagation and gradient descent to update the model's parameters. We will use the validation set to tune our hyperparameters, such as the learning rate, batch size, and number of epochs.

## Evaluation
We have evaluated the performance of our model on the testing set, using metrics such as accuracy, precision, recall, and F1 score. We will also perform a qualitative analysis of our model's predictions, examining examples of correctly and incorrectly classified news articles.
