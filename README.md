## Overview

This project contains a Convolutional Neural Network (CNN) model for sentiment analysis. The model is designed to classify text data into different sentiment categories. It achieved an accuracy of 62.505% on the test set.

## Model Architecture

Link to the Model's state Dictionary: ['https://drive.google.com/file/d/1xwvSkzGLUesM22cB21TVxH4Xdw0LEHVM/view?usp=drive_link']

The CNN model is built using PyTorch and includes the following layers:

- An **Embedding Layer** to convert text data into dense vector representations: 300 dimensional Embeddings ['https://drive.google.com/file/d/1vTBJ0CerCJ_3RQgw7op9MJNC_Fjs7cis/view?usp=drive_link']
- Convolutional layers
- Fully connected layers
- Dropout for regularization

## Requirements

Here are the packages used in the project:

- PyTorch
- Pandas
- NLTK
- Gensim
- Stanza
- Matplotlib
- Keras
- Scikit-learn
- Snowballstemmer

Install them using:

`pip install -r requirements.txt`

## Dataset

The dataset used for this project consists of 100,000 reviews of hotels in Arabic (All varying in lengths). It was originally stripped of any diacretics from the get go and It is proper arabic and not any specific dialect.

## Training

The model was trained for 10 epochs using the provided training script (`CNN.ipynb`).

## Usage

To run the model:

1. Load the model using the provided state dictionary ['https://drive.google.com/file/d/1xwvSkzGLUesM22cB21TVxH4Xdw0LEHVM/view?usp=drive_link'].
2. Prepare your input data in the same format as the training data.
3. Run the model to get sentiment predictions.

## Evaluation

The model was evaluated on a test set and achieved a maximum accuracy of 62.505%. The details of the evaluation can be found in the notebook `CNN.ipynb`.

## Contact

For any queries regarding this project, please contact [zaamountaha@gmail.com].
