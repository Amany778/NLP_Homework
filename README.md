# Bitcoin and Ethereum NEWS Analysis
There's been a lot of hype in the news lately about cryptocurrency, this script check the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.
We also apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. In addition we apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.




##  Files
crypto_sentiment.ipynb


## Details

### 1 - Sentiment Analysis
We use the newsapi to pull the latest news articles. Then, we use the Vader Sentiment Analysis to determine:
  1.  Which coin had the highest mean positive score
  2.  Which coin had the highest negative score?
  3.  Which coin had the highest positive score?


### 2 - Natural Language Processing
In this section, We use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins.


### 3 - Named Entity Recognition
In this section, We build a named entity recognition model for both coins and visualize the tags using SpaCy.


