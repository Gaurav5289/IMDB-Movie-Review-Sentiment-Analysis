# 🎬 IMDB Movie Review Sentiment Analysis Project

## 🎯 Objectives

Perform binary sentiment classification (positive/negative) on movie reviews.

Use LSTM (Long Short-Term Memory) network to capture temporal dependencies in text.

Build a real-time system to classify new reviews based on trained model.

# 🛠 Tools & Technologies

Python: Data preprocessing, modeling, evaluation.

TensorFlow, Keras: Deep learning model development (LSTM).

Pandas, NumPy: Data manipulation and preparation.

Kaggle API: Access to the IMDB reviews dataset.

# 🌟 Key Features

## 🧹 Data Preprocessing

Loaded and cleaned 50,000 IMDB movie reviews.

Converted sentiment labels (positive/negative) to binary values (1/0).

Tokenized reviews and padded sequences to uniform length (maxlen = 200).

Split data into training and testing sets (80/20 split).

# 🧠 Model Training (LSTM)

Used Embedding layer to convert tokens into dense vectors.

Implemented an LSTM layer with dropout and recurrent dropout for regularization.

Added final Dense layer with sigmoid activation for binary classification.

Trained model for 5 epochs with validation split to monitor overfitting.

# 🧪 Model Evaluation

Achieved ~86% accuracy on unseen test data.

Evaluated performance using loss and accuracy metrics.

Model was able to generalize well across diverse review patterns.

# 🔮 Real-Time Prediction
Developed a predict_sentiment() function to classify new user-provided text reviews.

Automatically tokenizes, pads, and feeds the input to the trained LSTM model.

Outputs sentiment prediction: positive or negative.
