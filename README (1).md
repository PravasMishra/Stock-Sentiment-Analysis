# Stock Sentiment Analysis

This repository contains code and data for performing sentiment analysis on stock-related news headlines. The goal is to analyze the sentiment of news headlines and understand their impact on stock market movements.

## Contents

- `Sentimental_Analysis.ipynb`: Jupyter notebook containing the code for sentiment analysis.
- `Data.csv`: CSV file containing news headlines and sentiment labels.

## Data

The `Data.csv` file consists of the following columns:

- `Date`: The date of the headlines.
- `Label`: Sentiment label (0 for negative, 1 for positive).
- `Top1` to `Top25`: News headlines for the respective date.

## Requirements

To run the notebook, you need to have the following Python packages installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `nltk`
- `matplotlib`
- `seaborn`

You can install these packages using `pip`:

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn
