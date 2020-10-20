# Text Analytics on Yelp Reviews
The project includes Text analysis of Yelp reviews under the ‘Restaurant’ category and for the state of Arizona only as it had the maximum number of reviews.
Next I have performed NLP tasks such as POS tagging, NER, WordCloud generation, Sentiment Analysis using Textblob and Vader.

  # - Data Exploration
  From the dataset, we found that there were reviews pertaining to 7812 restaurants in 55 cities, given by about 400,000 users. The time period of the dataset ranged from February 2005 to November 2019.

  # - Data Pre-processing
  Steps such as Tokenisation, Stop Word Removal, Lemmatization and other text cleaning activities were performed to transform the data for further analysis.

  # - Sentiment Analysis
  Using sentiment analysis, we will try to extract the sentiment of each review after processing the text data and compare them to the ratings given by the user for that review (which are the human labels). 
  I have implemented two lexicon-based sentiment analyzers: ‘TextBlob’ and ‘Vader’, to identify the sentiment polarity of the reviews. 

  # - Sentiment Polarity Classification
  Sentiment Polarity classification is done using ‘Naïve Bayes’ classifiers to help restaurants classify new reviews in yelp as positive or negative. 
  The model evaluation is performed by computing the accuracy of the classifiers and since the classes are found to be imbalanced, ROC AUC of the classifiers were also computed, which provided a better metric to pick the best performing model.
