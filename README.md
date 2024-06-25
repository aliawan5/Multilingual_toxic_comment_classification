# Multilingual_toxic_comment_classification
Multilingual toxic comment classification is basically classifiy the comment into two classes of toxic and non toxic and work with multiple language like English,Turkish, spanish and itaian

This repository contains distilled version of BERT (Bidirectional Encoder Representations from Transformers) for natural language processing tasks. DistilledBERT is a smaller and faster version of BERT, making it suitable for production environments with limited computational resources.

Data Loading and Preprocessing
The notebook likely includes code for loading and preprocessing data, which typically involves:

Loading a dataset (e.g., CSV, JSON)
Tokenizing the text data using BertWordPieceTokenizer
Preparing input tensors for the model
Model Definition
A neural network model is defined using Keras, leveraging the pre-trained DistilledBERT model from the transformers library. This involves:

Defining the input layers
Loading the pre-trained DistilledBERT model
Adding custom layers (e.g., Dense, Dropout)
Compiling the model with an appropriate optimizer and loss function
Training
The model is trained using the processed data. The training process includes:

Defining callbacks such as EarlyStopping and ModelCheckpoint
Fitting the model to the training data
Evaluating the model's performance on validation data
