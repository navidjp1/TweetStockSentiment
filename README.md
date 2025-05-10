# Setup

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
