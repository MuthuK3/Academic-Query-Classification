# Academic-Query-Classification

This project demonstrates how to perform text classification using a Recurrent Neural Network (RNN) in TensorFlow. The model is trained on a dataset of text documents labeled with categories, and it predicts the category of unseen documents.

## Dataset

The dataset consists of text documents and their corresponding categories. The text documents are preprocessed to remove stopwords and tokenized before being used to train the model.

## Model Architecture

The model architecture includes an Embedding layer followed by an LSTM layer and a Dense output layer with a sigmoid activation function. The model is compiled with binary crossentropy loss and the Adam optimizer.

## Training the Model

The model is trained on the preprocessed text data using a batch size of 64 and for 50 epochs. The training data is split into training and validation sets to evaluate the model's performance.
