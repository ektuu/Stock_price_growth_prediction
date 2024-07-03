
Long-Term Stock Price Growth Prediction using NLP on 10-K Financial Reports


Project Overview
This project aims to build an NLP pipeline that analyzes 10-K financial reports of publicly traded companies to predict their long-term stock performance. We leverage the Loughran-McDonald Master Dictionary, which contains words specifically curated for financial contexts, to uncover hidden signals in these comprehensive annual reports.


Background
10-K reports are comprehensive annual filings required by the U.S. Securities and Exchange Commission (SEC) for all publicly traded companies. These reports contain detailed information about:
Business operations
Risk factors
Selected financial data
Management's discussion and analysis (MD&A)
Financial statements and supplementary data


Objective
Our goal is to develop a machine learning model that can:
Ingest and process 10-K reports from various companies
Apply NLP techniques using the Loughran-McDonald Master Dictionary
Extract meaningful features and sentiment from the text
Predict long-term stock price growth potential


Key Components
Data Collection: Scraping or API-based retrieval of 10-K reports from SEC EDGAR database
Text Preprocessing: Cleaning, tokenization, and normalization of report text
Feature Extraction: Utilizing the Loughran-McDonald Master Dictionary for finance-specific sentiment analysis
Machine Learning Model: Developing and training a model to predict long-term stock performance
Evaluation: Assessing model performance against historical stock data


Technologies Used
Python
Natural Language Processing libraries (e.g., NLTK, spaCy)
Machine Learning frameworks (e.g., scikit-learn, TensorFlow)
SEC EDGAR API for data retrieval
Pandas for data manipulation
Matplotlib/Seaborn for visualization
