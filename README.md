# TextGeneration
---
This repository contain Text Generation result using LSTM. Model is within "Models" folder named as "weights-improvement-100-0.7746-bigger.hdf5". Jupyter notebook named "LSTM_Text_Generation.ipynb" contains code for model training and generating text.

The following improvements were made on top of the model:
>1) Predicted 500 characters only.

>2) Removed all the punctuation from the source text.

>3) Trained the model on padded sequences (Links to an external site.) rather than random sequences of characters. 

>4) Trained the model for 100 epochs.

>5) Added dropout to the input layer, remove it from the layer before dense layer. Used Dropout value of 0.1 everywhere.
