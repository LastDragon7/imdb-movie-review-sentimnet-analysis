# IMDb Movie Review Sentiment Analysis
This project involves performing sentiment analysis on IMDb movie reviews using four different machine learning models: Gaussian Naive Bayes (GaussianNB), Multinomial Naive Bayes (MultinomialNB), Bernoulli Naive Bayes (BernoulliNB), and Logistic Regression. Our objective is to classify the sentiment of movie reviews as either positive or negative. Among these models, Logistic Regression performs the best with an accuracy of 87%.

# Introduction
Sentiment analysis is a crucial task in natural language processing (NLP) that involves determining the sentiment behind a piece of text. This project focuses on analyzing IMDb movie reviews to classify them into positive or negative sentiments. We use four different classifiers to perform this task and compare their performance.

# Dataset
The dataset used for this project is the IMDb movie review dataset, which contains 50,000 movie reviews labeled as either positive or negative. The dataset is preprocessed to remove noise and convert text data into numerical features suitable for machine learning models.

# Models
We employ the following machine learning models for sentiment analysis:

**Gaussian Naive Bayes**

*GaussianNB assumes that the features follow a normal distribution. This model is suitable for continuous data.*

**Multinomial Naive Bayes**

*MultinomialNB is designed for multinomially distributed data, making it appropriate for text classification tasks where word frequency is important.*

**Bernoulli Naive Bayes**

*BernoulliNB works with binary/boolean features. It is useful when the input data is binary, such as the presence or absence of words in a document.*

**Logistic Regression**

*Logistic Regression is a linear model for binary classification that predicts the probability of a binary outcome. It works well with high-dimensional sparse data, making it ideal for text classification tasks.*

# Results
The performance of the models is evaluated based on their accuracy. Here are the results:

1. Gaussian Naive Bayes: Accuracy - 78.56%
2. Multinomial Naive Bayes: Accuracy - 82.89%
3. Bernoulli Naive Bayes: Accuracy - 83.14%
4. Logistic Regression: Accuracy - 86.09%

**Logistic Regression outperforms the other models with an accuracy of 86.09%.**
