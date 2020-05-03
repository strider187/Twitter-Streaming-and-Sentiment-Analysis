# Twitter-Streaming-and-Sentiment-Analysis
In this repository, I stream data from Twitter using Tweepy and also perform Sentiment Analysis on about 200 tweets using VaderSentiment and Naive Bayes Classifier from nltk.

## Requirements
#### Tweepy
Tweepy is an easy-to-use Python library for accessing the Twitter API. You can have a look at the [docs here.](https://www.tweepy.org/) To install Tweepy use the command:<br />
`pip install tweepy`<br />
#### JSON
JSON (JavaScript Object Notation) is a lightweight data-interchange format. Head over to this [page](https://www.json.org/json-en.html) to have a look at the docs. To install JSON library, ue the command:<br />
`pip install jsonlib`<br />
#### Pandas
Pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language. Pandas user guide and documnetation is avaiable [here](https://pandas.pydata.org/). To install pandas, use the command:<br />
`pip install pandas`<br />
#### Numpy
NumPy is the fundamental package for scientific computing with Python. To know more about numpy, visit this [page](https://numpy.org/). Tp install numpy, use the command:<br />
`pip install numpy` <br />
#### re - Regular expression operations
You can have a look at this [page](https://docs.python.org/3/library/re.html) to know more about re. To install re, use the command: <br />
`pip install regex`<br />
#### VaderSentiment
VADER Sentiment Analysis. VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains. Have a look at the project page [here](https://github.com/cjhutto/vaderSentiment). The pip install command for VaderSentiment is:<br />
`pip install vaderSentiment`<br />
#### nltk - Natural Language Toolkit
NLTK or Natural Language Toolkit is a leading platform for building Python programs to work with human language data. Head over to this [page](https://www.nltk.org/) to take a look at the documentation of nltk. To install nltk, use the following command:
<br /> `pip install nltk` <br />
In this project, I have used quite a few nltk modules especially, the nltk.corpus modules. There are a number of datasets which have been downloaded from the nltk.corpus module. The packages are:
- Stopwords
- Twitter Samples (twitter_samples)
To download these modules, simply swtich your command line to Python mode by simply using the `python` command. <br />
Once in the python mode, use the following set of command: <br />
`import nltk` <br />
`nltk.download('PACKAGE NAME')` <br />
A good example of this is: `nltk.download('stopwords')`
