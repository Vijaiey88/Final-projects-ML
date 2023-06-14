# Twitter Sentiment Analysis

This project focuses on analyzing the sentiments of tweets on the social networking website Twitter. The goal is to build a classification model that predicts the polarity (negative, neutral, or positive) of tweets.

## Dataset

The dataset used in this project is obtained by scraping Twitter using the Twitter API. It contains 1,600,000 tweets, each labeled with a sentiment score (0 = negative, 2 = neutral, 4 = positive). The dataset has the following fields:

1. target: The polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
2. ids: The ID of the tweet
3. date: The date of the tweet
4. flag: The query (NO_QUERY if there is no query)
5. user: The user that tweeted
6. text: The content of the tweet

## Steps

1. Data Preprocessing:
   - Read the dataset using Pandas.
   - Clean the text data by removing URLs, hashtags, mentions, special characters, numbers and converting to lowercase.
   - Remove stopwords from the text.

2. Feature Extraction:
   - Convert the preprocessed text data into numerical features using TF-IDF vectorization.

3. Model Selection and Training:
   - Split the dataset into training and testing sets.
   - Train a Logistic Regression model on the training data.

4. Model Evaluation:
   - Predict the sentiment labels for the testing data using the trained model.
   - Evaluate the model's performance using accuracy, classification report, and confusion matrix.

## Usage

To run the code, you need to have the following dependencies installed:
- pandas
- nltk
- scikit-learn

1. Download the 'twitter_dataset.csv' file and place it in the same directory as the code.
2. Run the code in a Python environment (e.g., Jupyter Notebook or any Python IDE).
3. The accuracy, classification report, and confusion matrix of the trained model will be printed.


## Further Improvements

- Explore other classification algorithms such as Random Forest, SVM, Naive Bayes, or neural network models like LSTM or CNN for comparison.
- Perform more in-depth exploratory data analysis (EDA) on the dataset.
- Tune hyperparameters of the models to improve their performance.
- Apply techniques like word embeddings (e.g., Word2Vec or GloVe) for better representation of text data.
- Handle class imbalance if present in the dataset.

