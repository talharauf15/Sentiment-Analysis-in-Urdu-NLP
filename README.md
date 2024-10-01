# Sentiment Analysis and Sarcasm Detection in Urdu

This project performs sentiment analysis and sarcasm detection on Urdu text, specifically social media posts. It includes text preprocessing, feature extraction using TF-IDF, and machine learning models like Logistic Regression and Naive Bayes to classify sentiment and detect sarcasm.

## Features
- Sentiment classification (Positive/Negative)
- Sarcasm detection
- Text preprocessing (removing stopwords, emojis, punctuation)
- Feature extraction using TF-IDF

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/talharauf15/Sentiment-Analysis-in-Urdu-NLP.git
   cd sentiment-analysis-in-urdu
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

- Preprocess Urdu text and remove noise (stopwords, punctuation, etc.).
- Train the model on the dataset:
   ```bash
   python src/train_model.py
   ```
- Detect sarcasm using:
   ```bash
   python src/sarcasm_detection.py
   ```

## License
This project is licensed under the **MIT License**.
