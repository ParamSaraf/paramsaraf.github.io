---
layout: post
title: Transformers for Time-Series
subtitle: Excerpt from Soulshaping by Jeff Brown
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [books, test]
---

Forecasting still remains to be dominated by Statistical techniques like ARIMA, SARIMA, etc. due to their ease of use and interpretation, although there have been Neural Network competitors for a while based on RNN and LSTM, but they are still not as popular due to the complexity in setup hyperparameters tuning.
Recent Kaggle Competitions showed the trend towards Neural Network-based models like N-Beats (M4 Competition winner is a hybrid model of Exponential Smoothing and dilated LSTM ), Amazon’s DeepAR, MXNet based GluonTS and now the trend is moving towards Transformer based models for Time Series after their huge success in NLP.
Temporal Fusion Transformer (or TFT) is one such model, created by the Google — a novel attention-based architecture which combines high-performance multi-horizon forecasting with interpretable insights into temporal dynamics. It utilizes recurrent layers for local processing and interpretable self-attention layers for learning long-term dependencies
Although, one can directly access Google’s TFT and Apache’s GluonTS but they are difficult to implement, especially GluonTS being built on MXNet architecture. ‘PyTorch Forecasting’ package makes it easy to use state of the art Deep Learning models like TFT and N-Beats for forecasting problems. Although it’s still in the early stages and the dream state would be huggingface type of libraries for Forecasting, but it is worth trying
