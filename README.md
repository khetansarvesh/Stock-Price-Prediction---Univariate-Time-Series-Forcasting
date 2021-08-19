# Stock-Price-Prediction---Univariate-Time-Series-Forcasting

In this project, I have implemented a 4 hidden layer stacked LSTM RNN architecture to solve the univariate time series forcasting problem of google stock price prediction using pytorch deep learning library.

To understand theory go to my notes at following link (recommended) : https://drive.google.com/drive/folders/19D3bWmZKLKKCD8jgL71KzFzmtmP9pIBS?usp=sharing
In my notes I have given a detailed explaination of how one can solve the univariate time series problem using even a FFNN but since there exists a problem in solving with FFNN it motivated the idea of RNN, what is this problem?? Read my notes to understand same. Now there exists a problem with RNN i.e. vanishing and exploding gradients which motivates the idea of LSTMs and since these exists a problem with LSTMs it motivated the idea of GRUs. To solve the parallel computation problem with GRUs the idea of transformer based models poped up.

Dataset can be found at following link : https://drive.google.com/file/d/1hVhxy6DMIKRpN3tGQ4JSGIgLMlORb3MA/view?usp=sharing

Please refer to following link for entire code implementation : https://colab.research.google.com/drive/1BoAdZXZaXJFMWoQoCww3ytDVFd2Ha3P5?usp=sharing
