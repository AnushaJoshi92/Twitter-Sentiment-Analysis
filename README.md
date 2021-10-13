# Twitter-Sentiment-Analysis

Sentiment analysis with 1.4 million labelled tweets

Steps:
1. Pre-processing data: Remove username handles, remove URL links, remove non-alpha numeric characters, remove duplicates, replace emojis, perform lemmatization, remove numbers
2. Tokenization using RegExpTokenizer
3. Converting words to vectors using Tfidf vectorizer along with removing stop words
4. Split the data into train and test 
5. Use logistic regression to train data using training set and test the model using test set
6. Calculate accuracy and plot confusion matrix
