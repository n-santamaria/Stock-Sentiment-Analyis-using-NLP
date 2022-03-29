# Stock-Sentiment-Analyis-using-NLP


### About the dataset

- The dataset contains news and stock price shifts.
- There're 25 columns containing top news for each day.
- Depended column containing value either 0 or 1.
    - 0 = Decrease or same stock price.
    - 1 = Increase in stock price.
- Data ranges from 2000 to 2016 where data from 2000 to 2008 was scrapped from Yahoo finance.


### Pre-processing
- Removal of stop words using nltk library.
- Removal of stop words using regrex.
- For every row, merging all the news into one sentence.
- Applying CountVectorizer or TFIDF for converting the sentence into document matrix.


### Model creation
- Applying Random Forest Classifier for model creation.


### Model evaluation
- Using Classification report, Confusion matrix, Accuracy score for evaluating the model.