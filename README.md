# NLP_application
Apply Natural Language Processing to perform sentiment analysis and named entity recognition.

## 1. Background 

Hype in the news is a great indication for the current public sentiment around various matters from politics to investment decisions to environmental matters.

The purpose of this exercise is to pull the latest news articles on Bitcoin and Ethereum from [newsapi](https://newsapi.org/) to apply natural language processing to understand the sentiment thereof. Fundamental NLP techniques is applied to better understand ther factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.



## 2. Sentiment Analysis
The latest articles for Bitcoin and Ethereum is extracted from News Api and imported into a DataFrame to compare sentiment scores of the 2 coins.

### Findings
When comparing the sentiment analysis of news articles of Bitcoin and EthereumFrom this results, the following results can be summarised:
* Bitcoin had the highest mean positive score
* Ethereum had the highest compound score
* Ethereum had the highest positive score

## 3. Natural Language Processing
NLTK and Python was used to tokenize the text for Bitcoin and Ethereum. 

For each word the following was performed through a function that was defined upfront:
* list of words created
* all words converted to lowercase
* punctuation removed
* lemmatization of words into root words
* stopwords removed - and the default list of stopwards expanded

### 3.1 N-gram analysis
The ngrams and word freqeuncy for Bitcoin and Ethereum was analyzed:
* NLTK was used to produce the n-grams, for N=2
* Top 10 words for each coin was listed

### 3.2 Word Clouds:
Word clouds were generated for each coin to summarize the news highligts:

Bitcoin Word cloud:

![bitcoin_wordcloud.png](Images/bitcoin_wordcloud.png)

Ethereum Word Cloud:

![ethereum_wordcloud.png](Images/ethereum_wordcloud.png)

### 3.3 Named Entity Recognition
A named entitiy recognition model was built for both Bitcoin and Ethereum and the tags visualized using SpaCy.


## 4. Files to be used for the purposes of this modeling exercise.

[Crypto Sentiment Jupiter Notebook](crypto_sentiment.ipynb)





