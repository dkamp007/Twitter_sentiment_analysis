# Twitter_sentiment_analysis

1. Downloaded the data from kaggle with a shape of (1600000, 6).
2. Cleaned the data & removed all the stopwords using the stopwords module from NLTK.
3. Using Porter Stemmer, the tweets have been stemmed & stored as a separate feature.
4. Performed train_test_split on the stemmed data & filled up any missing values arising from this.
5. Transformed the stemmed text data into vectors using the TfidfVectorizer from sklearn.
6. Using Logistic Regression fitted the 80% split data & trained the model.
7. Using the 20% split data to evaluate the performance of the model. The accuracy score for the test data turned out to be 78%. Whereas the train accuracy was 81%.
