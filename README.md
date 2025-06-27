# Sentiment Analysis of Product Reviews Using GPT API

This is my research-based Final Year Project (FYP), which performs sentiment analysis on Amazon mobile electronics reviews using a Large Language Model (GPT model) accessed via OpenAI API. The sentiment prediction process is automated, in which the model analyzes, infers, and classifies the product reviews as either **Positive** or **Negative** only based on the review text instead of misled by the potentially incorrect star rating that might cause misclassification.

## Features
- Utilizes GPT-3.5 Turbo API for accurate, text-based sentiment classification
- Dataset from Hugging Face
- 16 preprocessing steps, including tokenization, lemmatization, stopwords removal
- Model training, train-test split, and model evaluation
- Lightweight and ready to run on Google Colab
- Code provided in .py and .ipynb formats

## Setup Instructions
- Run via Colab or Python script
- Add your OpenAI API key inside the notebook/script. For Colab, use the Secret feature in Colab to protect your key
