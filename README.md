# Sentiment-Analysis-on-Hotel-Review

## Objective:

The goal of this project is to perform sentiment analysis on hotel reviews using natural language processing (NLP) techniques. The dataset comprises user reviews with associated sentiment labels (happy or not happy). The sentiment analysis aims to determine the sentiment expressed in each review.

## Dataset Description:

The dataset used in this sentiment analysis project focuses on hotel reviews, encompassing various aspects of user experiences. Each entry in the dataset consists of specific attributes, including User_ID, Description (textual review), Browser_Used, Device_Used, and Is_Response (sentiment label - 'happy' or 'not happy').

## Data Preprocessing:

-- Converted text to lowercase.
-- Removed HTML tags, punctuation, and stopwords to clean the text data.
-- Applied Term Frequency-Inverse Document Frequency (TF-IDF) to convert the textual data into numerical vectors, capturing the importance of words in each document.

## Model Training:
Utilized logistic regression as the classification algorithm to train the sentiment analysis model. Achieved an accuracy of 88% on the training dataset.

## Evaluation:
Evaluated the model's performance on new, unseen reviews to ensure generalizability. The model demonstrated reliable sentiment prediction capabilities.

## Results:

Accuracy: The trained model achieved an accuracy of 88%, indicating its effectiveness in classifying sentiments.

Generalization: Successfully evaluated on new reviews, demonstrating the model's ability to generalize well to unseen data.


## Conclusion:

This project showcases a sentiment analysis model trained on hotel reviews, providing insights into customer sentiments. The combination of data preprocessing, TF-IDF transformation, and logistic regression yields a reliable model for sentiment classification. The achieved accuracy of 88% suggests the model's proficiency in discerning sentiments expressed in hotel reviews. The code and model can be further refined and potentially deployed for practical applications in the hospitality industry.




