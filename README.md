# python-assignment
An assignment on the Sentiment Analysis on the IMDB Reviews

# libraris-used
    pandas: This library is used to read and write the data into the CSV file.
    re: This library is used for the regular expression for the purpose of removing the numerals from the text.
    BeautifulSoup: This libarary is used for removing the unnecassary html tags.
    Pool: This library is used to implement the multiprocessing in the long running loops.
    CountVectorizer: This library is used to initialising the parameters for creating the features in the Bag of Words.
    stopwords: This library is used to remove the words like 'a','an','the','is' etc. This helps in fetching just the important and meaningful words.

# algorithm-used
    In this Sentiment Analysis Program, the features are created according to the concept of the Bag of Words and then the implementation of SVC, i.e Support Vector Classifier is done.

# running-the-program
    The program can be run by the following command:
        python main.py