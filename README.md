Project Overview

This project applies Natural Language Processing (NLP) and Machine Learning techniques to classify text messages as spam or legitimate.
It is trained on a dataset of labeled messages and uses the Naive Bayes classifier for prediction.
 Technologies Used

Python 

Streamlit (for UI)

Scikit-learn (for model building)

Pandas & NumPy (for data handling)

Pickle (for model saving/loading)

How It Works

Data Preprocessing – Clean and prepare the text data (removing punctuation, stopwords, etc.).

Feature Extraction – Convert text into numerical features using TfidfVectorizer.

Model Training – Train a Naive Bayes classifier on the preprocessed dataset.

Prediction – Load the trained model and classify new messages in a Streamlit web app.
