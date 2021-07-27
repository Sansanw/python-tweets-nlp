# python-tweets-nlp
Analyzing Trump’s Tweets Using Natural Language Processing

# import data

```
# Working with dates
from datetime import datetime as dt
from pytz import timezone

# Data cleaning, analysis
import pandas as pd
import numpy as np

# Data Visualization
import matplotlib as mpl
from matplotlib import pyplot as plt
import seaborn as sns
%matplotlib inline

# Natural Language Processing
import nltk, re, string
from nltk import word_tokenize
from nltk.stem import WordNetLemmatizer
from nltk.corpus import stopwords
from nltk.util import ngrams
from nltk.corpus import wordnet
from collections import Counter
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')


# VADER Sentiment Analyzer from NLTK
from nltk.sentiment import SentimentAnalyzer
from nltk.sentiment.util import *
from nltk.sentiment.vader import SentimentIntensityAnalyzer
nltk.download('vader_lexicon')

# Hide warnings
import warnings
warnings.filterwarnings('ignore')

# Ensure that pandas dataframs are able to print
pd.set_option('display.max_columns', 10)
```
