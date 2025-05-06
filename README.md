# 🧠 Next Word Predictor with LSTM

This is a simple web application built using **Streamlit** that predicts the next word in a sequence using an **LSTM (Long Short-Term Memory)** neural network. The model was trained on a corpus of English literature and is capable of basic next-word prediction based on context.

## 🚀 Demo

Enter a sentence like:

And get the next word predicted by the model!

## 📁 Project Structure

- `app.py`: Main Streamlit application that loads the trained model and tokenizer, and runs the user interface.
- `next_word_lstm.h5`: Pre-trained LSTM model (not included here).
- `tokenizer.pickle`: Fitted tokenizer object used during training (not included here).
- `experiments.ipynb`: Jupyter Notebook with model training, preprocessing, and experimentation.

## 🛠️ How It Works

1. **Input**: User enters a sequence of words.
2. **Tokenizer**: Converts input text to sequences.
3. **Padding**: Ensures proper input length for the model.
4. **Prediction**: LSTM model predicts the most probable next word.
5. **Output**: The predicted word is displayed on the screen.
