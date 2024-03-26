# Financial News Extraction and Stock Market Forecasting

This project focuses on extracting financial news-based tweets from Twitter and utilizing the extracted data to train both a BERT model and a sequence-to-sequence (seq2seq) model. Additionally, it incorporates the use of a Prophet model for univariate forecasting of stock market data.

## Overview

The project involves two main components:

1. *Financial News Extraction from Twitter:* 
   - Utilized Twitter API to extract financial news-related tweets.
   - Implemented filtering techniques to isolate tweets relevant to the stock market and financial news.
   - Processed and cleaned the extracted data for further analysis.

2. *Model Training:*
   - *BERT Model:*
     - Used the extracted financial news tweets to train a BERT (Bidirectional Encoder Representations from Transformers) model.
     - Fine-tuned the BERT model to understand and analyze financial language and sentiments.
   - *Seq2Seq Model:*
     - Trained a sequence-to-sequence model to generate summaries or analyze the financial news tweets.
     - Implemented attention mechanisms to capture the relevant information in the tweets.
   
3. *Stock Market Forecasting using Prophet Model:*
   - Utilized the Prophet model for univariate time series forecasting of stock market data.
   - Analyzed historical stock market data to predict future trends and fluctuations.

## Requirements

- Python 3.x
- Twitter API credentials
- PyTorch for BERT and seq2seq models
- Prophet library for stock market forecasting
- Other necessary Python libraries: pandas, numpy, matplotlib, etc.

## Usage

1. *Financial News Extraction:*
   - Run the Twitter API script to extract financial news-related tweets.
   - Clean and preprocess the extracted data as necessary.

2. *Model Training:*
   - Prepare the data for training the BERT and seq2seq models.
   - Fine-tune the BERT model with the financial news data.
   - Train the seq2seq model using the preprocessed financial news tweets.

3. *Stock Market Forecasting:*
   - Obtain historical stock market data for the desired market.
   - Use the Prophet model to forecast future trends in the stock market.

## Future Improvements

- Incorporate more advanced NLP techniques for sentiment analysis and topic modeling of financial news tweets.
- Explore ensemble methods for combining the predictions of the BERT and seq2seq models.
- Enhance the Prophet model with exogenous variables for improved stock market forecasting accuracy.
