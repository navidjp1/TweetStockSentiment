# Stock Tweet Sentiment Analysis to Predict Stock Price Movement
This project evaluates the performance of different sentiment classifers and ML models in terms of predicting whether a company stock will go up or down on a certain day

## Dataset

Obtained from Kaggle: [Stock Tweets for Sentiment Analysis and Prediction](https://www.kaggle.com/datasets/equinxx/stock-tweets-for-sentiment-analysis-and-prediction)

### Sentiment Classification Models:

[FinBERT](https://huggingface.co/ProsusAI/finbert)

[VADER](https://github.com/cjhutto/vaderSentiment)

[RoBERTa](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest)

[Emotion English DistilRoBERTa](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)

## Setup

## Clone Repository

```bash
git clone https://github.com/navidjp1/TweetStockSentiment.git
```

## Create Python Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

### macOS/Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate.ps1
```

## Install Packages

```bash
pip install -r requirements.txt
```

## Load Large Dataset

In order to have the actual tweet_sentiment.csv file in your folder you must use Git LFS

### To Download

#### macOS

```bash
brew install git-lfs
```

#### Windows

Download from [Git LFS](https://git-lfs.com/)

### Once Downloaded, Initialize Git LFS

```bash
git lfs install
```

### Fetch Files

```bash
git lfs pull
```
