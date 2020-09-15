# 230T2 - Deep Learning for Time Series project

This repository includes the different work files of the project that was conducted as part of the requirements for 230T2 courses.
The paper that is replicated is the following: Constructing Financial Sentimental Factors in Chinese Market Using Natural Language Processing, available on ArXiv [here](https://arxiv.org/pdf/1809.08390v1.pdf).

The requirements for the project can be installed through the following command line:
> $ pip install -r requirements.txt

## Part 1: data retrieval and data engineering

This part focuses on getting the data and inputting it into a dataframe for easier manipulation in the next steps of the projects. The data set is included in the folder `reuters`.

The code in the notebook is also taking care of performance retrieval and labelling of the different headlines.

The notebook is named `230T2-data-exploration.ipynb`.

## Part 2: benchmark model
This part focuses on training naïve bayes classifier with tf-idf features, and compute the correlation of various benchmark classifiers with S&P500 price/returns. 

## Part 3: BERT model

This part is dedicated to using the data that was preprocessed in the first section and to train the final layer of a BERT model to have access to sentimental analysis.

The requirements are already including in the top of this document.

The notebook is named `230T2-bert-model.ipynb`.

## Part 4: backtest strategy
