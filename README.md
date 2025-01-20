# Shopee Flash Sale Reviews Sentiment Analysis

## Project Overview
The Shopee Flash Sale event is a popular e-commerce promotion where a variety of products are sold at discounted prices for a limited period. Customers often leave reviews to express their satisfaction or dissatisfaction with products. Analyzing these reviews helps businesses understand customer feedback, improve product quality, and enhance customer experience.

This project demonstrates how to:
- **Data scraping**: Create and pull reviews from Shopee Flash Sale event.
- **Preprocess text data**: Clean and prepare customer reviews for analysis.
- **Feature extraction**: Use techniques like **CountVectorizer** and **Word2Vec** to extract meaningful features from text data.
- **Model building**: Build machine learning and deep learning models (e.g., **LSTM**, **GRU**) to predict the sentiment of reviews.
- **Evaluate model performance**: Assess the accuracy and effectiveness of the models.

## Features
- **Data Preprocessing**: Handles text cleaning, tokenization, and vectorization of text reviews.
- **Sentiment Classification Models**: Implements deep learning models (LSTM and GRU).
- **CountVectorizer and Word2Vec**: Converts text data into numerical representations for machine learning algorithms.
- **Visualization**: Includes visualizations of model performance and sentiment distribution.
- **Multi-Class Sentiment Prediction**: Classifies reviews into three sentiment categories: Positive, Negative, and Neutral.

## Installation
To run this project, you need to have Python and the required libraries installed. You can install the dependencies by running:

```bash
pip install -r requirements.txt
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/hwamichelleangelina/shopee_flash_sale_reviews_sentiment_analysis.git
   ```

2. Navigate to the project folder:
   ```bash
   cd shopee_flash_sale_reviews_sentiment_analysis
   ```

3. Preprocess and clean the review data using the provided scripts.
4. Train sentiment analysis models (LSTM, GRU, etc.).
5. Evaluate model performance and generate results.

## Models Used
- **CountVectorizer + GRU**: For sentiment classification using a combination of simple text vectorization and a GRU-based neural network.
- **Word2Vec + LSTM**: A hybrid approach using pre-trained Word2Vec embeddings with an LSTM model for sequence-based sentiment analysis.
- **TF-IDF + LSTM**: For sentiment classification using a combination of TF-IDF and Long Short-Term Memory Model.

## Results
Model evaluation is carried out using various metrics such as:
- **Accuracy**: Overall performance of the model.
