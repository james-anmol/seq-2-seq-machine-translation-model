Preprocessing Data: Cleans and organizes text data from English and Hindi files into pairs of sentences.
Performs tokenization and creates dictionaries for mapping tokens to indices.

Model Architecture: Defines an encoder-decoder architecture using LSTM layers for sequence-to-sequence modeling.
Configures dimensionality, batch size, and number of epochs.
Specifies activation functions, return states, and input shapes for LSTM layers.

Model Compilation and Training: Compiles the defined model with Adam optimizer, categorical cross-entropy loss, and accuracy metric.
Trains the model using input data, target data, batch size, epochs, and validation split.
Saves the trained model for future use.
