# Shakespeare-LSTM

A character-level text generation model built with LSTM using TensorFlow/Keras.

## Features
- Shakespeare text preprocessing
- Character-level one-hot encoding
- LSTM-based next-character prediction
- Temperature-based text generation
- Trained model saving and loading

## Model

- Sequence length: 40
- LSTM units: 128
- Optimizer: RMSprop
- Loss: Categorical Crossentropy

## Temperature Sampling

The model generates text with different temperature values:

- 0.2 - more conservative
- 0.4
- 0.6
- 0.8
- 1.0 - more random