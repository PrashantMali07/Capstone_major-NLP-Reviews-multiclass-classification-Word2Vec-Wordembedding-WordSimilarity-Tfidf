# Capstone_major-NLP-Reviews-multiclass-classification-Word2Vec-Wordembedding-WordSimilarity-Tfidf

In this project, I have done multiple tasks:

1. Have done detailed EDA to provide meaningful insights, which helps to recognize the product quality as per the products rated by the customers.
2. Did NLP text preprocessing i.e., Tokenization, stemming, lowering etc.
3. Created two different vectors: a. Tfidf Vector (using all the features having 5 classes) b. Word2Vec vector h 500 features and a model to find similar words.
4. Modeling was done using RandoForest & DecisionTree Classifiers, however, in the end, I have decided to proceed with WordEmbedding RNN-based model to achieve better test accuracy, which I achieved and making it worth moving towards the Deep Neural network models.


# Problem Statement:

*You are working in an e-commerce company, and your company has put forward a task to analyze the customer reviews for various products. You are supposed to create a report that classifies the products based on the customer reviews.*

**Dataset Information:**
The Reviews.csv dataset contains 60145 rows and 10 columns.


* Id - Record ID
* ProductId - Product ID
* UserId - User ID who posted the review
* ProfileName - Profile name of the User
* HelpfullnessNumerator - Numerator of the helpfulness of the review
* HelpfullnessDenominator - Denominator of the helpfulness of the review
* Score - Product Rating
* Time - Review time in timestamp
* Summary - Summary of the review
* Text - Actual text of the review

# Tasks to be performed:

1. Find various trends and patterns in the reviews data, create useful insights that best describe the product quality.

2. Classify each review based on the sentiment associated with the same.
