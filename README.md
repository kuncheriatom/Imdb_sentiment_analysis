# Sentiment Analysis with RNN on IMDB Dataset

## Overview
This project implements a Recurrent Neural Network (RNN) using TensorFlow to classify movie reviews from the IMDB dataset as positive or negative.

## Steps

1. **Setup**
   - Load and preprocess the IMDB dataset.
   - Tokenize and pad text sequences.

2. **Model Building**
   - Construct an RNN with an Embedding layer, LSTM layer, and Dense layer.
   - Compile the model with binary cross-entropy loss and the Adam optimizer.

3. **Training**
   - Split data into training and validation sets.
   - Train the model with early stopping to prevent overfitting.

4. **Evaluation**
   - Assess model performance using accuracy and loss.
   - Visualize training progress with accuracy and loss plots.

5. **Optimization**
   - Tune hyperparameters like LSTM units, dropout rates, and learning rate.
   - Compare with a feedforward neural network.

## Results
The RNN model effectively classifies sentiments in movie reviews, outperforming a feedforward neural network.

## Conclusion
The project highlights the strengths of RNNs in handling sequential data for sentiment analysis tasks.
