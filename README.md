Next_word_prediction_NLP
This project demonstrates how to build a next-word prediction model using a Long Short-Term Memory (LSTM) network in TensorFlow/Keras. The model is trained on a text dataset and can predict the next word given a sequence of words as input.<br>
1. The code reads a text file and preprocesses it by splitting it into sentences and tokenizing the words.<br>
2. It creates input sequences (n-grams) for training the LSTM model.<br>
3. The LSTM model is defined and compiled with appropriate loss function, optimizer, and metrics.<br>
4. The model is trained on the prepared data for a specified number of epochs.<br>
5. After training, the model can predict the next word given a seed text.<br>
<br>
Usage
<br>
1. Provide your text data in a `.txt` file.<br>
2. Update the `file_path` variable with the path to your text file.<br>
3. Run the code to train the model and generate next-word predictions.<br>
4. Modify the `seed_text` and `next_words` variables to experiment with different inputs and prediction lengths.<br>
<br>
Dependencies
<br>
- TensorFlow<br>
- Keras<br>
- NumPy<br>
- regex<br>
<br>
Note<br>
The accuracy of the model depends on the quality and size of the training data. Experiment with different datasets and hyperparameters to improve performance.
