# Sentiment-Analysis-Using-NLP-ML
In this project we do this to do the sentiment analysis:-
 1. First, we collect the data and for sentiment analysis you need text, and you can collect it from kaggle or anyother sorces.
 2. we import all our dependcies means libraries to produce the high quality output.
 3. we use nlp to clean the text data and for this we use nltk library and regular expression library to remove unwanted symbols,numbers etc. from data.
 4. After that we import feature extraction model name tidfvectorizer to convert the clean text data into numerical data within range of 0 to 1 because the machine learning model can not work on text data.
 5. Then we use logistic regression model to classify whether the comment or tweet is positive or negative.
