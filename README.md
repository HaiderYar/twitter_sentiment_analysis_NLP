# twitter_sentiment_analysis_NLP

This repository contains a Jupyter Notebook that performs sentiment analysis on a dataset of tweets. The analysis is done using Natural Language Processing (NLP) techniques and a Logistic Regression model to classify tweets as positive or negative.

## Overview

The notebook includes the following steps:
1. **Data Preprocessing:** 
   - Importing the necessary libraries.
   - Cleaning and preprocessing the text data.
   - Converting text data into numerical features using TF-IDF Vectorization.

2. **Model Training:**
   - Splitting the data into training and testing sets.
   - Training a Logistic Regression model on the processed data.

3. **Evaluation:**
   - Evaluating the model's accuracy on the test data.
   - Analyzing the results and making conclusions.

## Dataset

The dataset used for this project is the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140), which is publicly available on Kaggle. It contains 1.6 million tweets, each labeled as either positive or negative, making it ideal for training a sentiment analysis model.

## Acknowledgements

- **GeeksforGeeks**: This project was inspired and guided by tutorials and articles from [GeeksforGeeks](https://www.geeksforgeeks.org/), which played a crucial role in understanding and implementing the machine learning and NLP techniques used in this notebook.

- **Kaggle**: The dataset used in this project was sourced from Kaggle, specifically from the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140).

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/HaiderYar/twitter_sentiment_analysis_NLP.git
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   You can run single cells or use the command below:
   ```bash
   jupyter notebook model.ipynb
   ```

## Contact
If you have any questions or suggestions, feel free to open an issue.