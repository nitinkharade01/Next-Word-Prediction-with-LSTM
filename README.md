# Next Word Prediction with LSTM

### Overview

This project is an AI-powered next-word prediction model using an LSTM (Long Short-Term Memory) neural network. The model is trained on textual data and predicts the next word in a given sentence. It utilizes TensorFlow, Keras, and Streamlit for deployment as a web application.

### Features

Uses LSTM for text generation

Trained on Shakespeare's "Hamlet"

Implements early stopping for optimal performance

Deployable as a Streamlit web app

### Installation

To set up the project, follow these steps:

1.Clone the repository:

git clone https://github.com/yourusername/next-word-lstm.git
cd next-word-lstm

2.Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3.Install dependencies:

pip install -r requirements.txt

### Usage

Run the Streamlit application:

streamlit run app.py

### Files in the Repository

next-word-lstm/
│── app.py                 # Streamlit application file.

│── experiemnts.ipynb       # Jupyter notebook for experiments.

│── hamlet.txt              # Training dataset (Hamlet text).

│── next_word_lstm.h5       # Trained LSTM model.

│── next_word_lstm_model_with_early_stopping.h5  # Model with early stopping.

│── tokenizer.pickle        # Tokenizer file for text preprocessing.

│── requirements.txt        # Dependencies for the project.

│── README.md               # Project description.

│── .gitignore              # Files to ignore in Git.

### Dependencies

The project requires the following dependencies:

tensorflow==2.15.0
pandas 
numpy 
scikit-learn
tensorboard
matplotlib
streamlit
scikeras
nltk

### Model Details

The model uses:

Tokenization with nltk

Sequence padding with TensorFlow/Keras

LSTM layers for next-word prediction

Early stopping to prevent overfitting

### Deployment

The model can be deployed using Streamlit on a cloud service such as AWS, Heroku, or Render.
