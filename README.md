# Autocomplete / Next Word Prediction model

##### Problem Statement: Predict the next word user likely to type based on current word.

This model has been traiend on the "News Category Dataset's"  headlines. Dataset can be found here: https://www.kaggle.com/rmisra/news-category-dataset

### The Model Architecture

The model has only 4 layers.

1. The first layer is an Embedding layer.
2. Followed by a GRU layer.
3. A Dropout Layer
4. Dense layer

Loss Function : SparseCategoricalCrossentropy
Optimizer: Adam

### Model Training

The model has been trained for 30 epochs. The loss started from 2.1 and reduced down to 0.85 by the end of 30 th iteration.

![alt text](https://github.com/mahesh863/next-word-prediction/blob/main/Graphs/Loss.png)
