
# Sentiment Analysis on @CTA Tweets using Machine Learning Algorithms :smiley: :satisfied: :smirk: :expressionless: :confused: :disappointed: :rage:


## Background

Sentiment analysis is using analytical and machine learning models to classify sentiment of the input sentence as positive or negative.

The goal of this project is to predict people's sentiments over last 10 days about CTA (Chicago Transit Authority) on twitter posts with NLP using  Python library Scikit-Learn.

This data is something that the CTA could start storing and keeping track of now. Then as each rennovation project is complete they can compare rider sentiment before, during, and after the rennovation. This would allow the CTA to confirm that the rennovations are seen by the public, as something that does infact improve rider expereince. 


![CTA_Twitter](Img/CTA_Twitter.png)

## Data Source and Models

The code uses the [tweepy](http://www.tweepy.org/) library to access the Twitter API.

We used [Airline Data](https://www.figure-eight.com/data-for-everyone/) obtained from Kaggle to train and test our data using various ML models and compared the score for each models.
First, we convert text data into number vectors using label encoder.
And then, we train vector data and its labels (Positive, Negative or Neutral) using training models.

- The models that we used are:
- Multinomial Naive Bayes
- Complement Naive Bayes
- Bernoulli Naive Bayes
- Decision Tree
- SVM (Support Vector Machine)
- Random Forest Classifier

![Scores](Img/Score.png)

After comparing each model, we found that SVM gives the maximum score of 78.38 %. So we used SVM on CTA Tweets data to predict the Sentiments.

![Sentiments](Img/Total_Tweets.png) ![Sentiments](Img/Pie_chart.png)


![Words](Img/WordCloud2.png)