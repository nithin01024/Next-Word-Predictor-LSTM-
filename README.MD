# Next Word Prediction using LSTM

A Deep Learning-based Next Word Prediction system using an LSTM (Long Short-Term Memory) neural network. The model is trained on Shakespeare's *Hamlet* text and deployed using Streamlit.

## Features

- Text preprocessing and tokenization
- N-gram sequence generation
- Word-level prediction using LSTM
- Trained using TensorFlow/Keras
- Interactive Streamlit web application

## Technologies Used

- Python
- TensorFlow / Keras
- LSTM
- NLP
- NLTK
- NumPy
- Pandas
- Scikit-learn
- Streamlit

## Dataset

The model is trained on Shakespeare's *Hamlet* text obtained from the NLTK Gutenberg corpus.

## Model Architecture

- Embedding Layer
- LSTM Layer (150 units)
- Dropout (20%)
- LSTM Layer (100 units)
- Dense Layer with Softmax activation

## Project Workflow

Hamlet Text → Tokenization → N-gram Sequence Generation → Padding → LSTM Training → Model Saving → Streamlit App → Next Word Prediction

## Project Structure

next-word-prediction-lstm/
- app.py
- next_word_lstm.keras
- tokenizer.pickle
- next_word_prediction.ipynb
- requirements.txt
- README.md

## How to Run

### Install Dependencies

### bash
pip install -r requirements.txt

### Run the Streamlit App
streamlit run app.py

The application allows users to enter a sequence of words and predicts the next word using the trained LSTM model.
Training
The model was developed and trained using Google Colab with GPU acceleration. The complete training process is available in the Jupyter Notebook included in this repository.
## Future Improvements
- Train on larger datasets
- Improve prediction accuracy
- Implement Top-K predictions
- Experiment with GRU and Bidirectional LSTM
- Deploy the application online
- Explore Transformer-based language models
Author
Sonnaila Nithin
B.Tech – Metallurgical and Materials Engineering
Indian Institute of Technology Bhubaneswar