# COVHINDIA : Deep Learning Model for Sentiment Classification on COVID19 Tweets from India

## Overview
Various variations of deep learning model to perform sentiment analysis on tweets related to COVID19 from India

## Datasets
1. Tweet dataset : [Kaggle dataset](https://www.kaggle.com/surajkum1198/twitterdata)
2. GloVe embeddings : [GloVe](https://www.kaggle.com/rtatman/glove-global-vectors-for-word-representation)
3. FastText embeddings : [FastText](https://www.kaggle.com/vsmolyakov/fasttext)
4. GloVe Twitter : [GloveTwitter](https://www.kaggle.com/bertcarremans/glovetwitter27b100dtxt)
5. Crisis Embeddings : [Crisis Embeddings](https://github.com/CrisisNLP/deep-learning-for-big-crisis-data)


| Model Description                         | Training Accuracy | Validation Accuracy | Notebook Link                                                                                                                                  |
|-------------------------------------------|-------------------|---------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| Basic LSTM                                | 85.1%             | 86.7%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| LSTM + GloVe Embeddings                   | 88.9%             | 90.9%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| LSTM + FastText Embeddings                | 92.5%             | 88.9%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| LSTM + Crisis Embeddings                  | 83.4%             | 84.7%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| Basic Bi-directional LSTM                 | 87.3%             | 86.0%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| Bi-directional LSTM + GloVe Embeddings    | 91.2%             | 90.6%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| Bi-directional LSTM + FastText Embeddings | 88.3%             | 88.6%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| Bi-directional LSTM + Crisis Embeddings   | 86.0%             | 85.1%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bi-lstm-glove-fasttext-crisis.ipynb) |
| BERT                                      | 99.7%             | 93.8%               | [Notebook](https://github.com/purvasingh96/Sentiment-Analysis-via-Deep-Learning-Model/blob/main/covhindia-bert.ipynb)                          |

## References

[Paper on sentiment analysis](https://ieeexplore.ieee.org/abstract/document/9207881)<br>

[Using NMT/HSWN for sentiment analysis on Hindi tweets](https://github.com/shubham721/Sentiment-Analysis-On-Hindi-Reviews/blob/22026e569c9e92bc7d89a0de3dad82d4b1672525/ResourceBasedSentimentClassification.py)


