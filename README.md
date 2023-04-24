# Stock forecasting using ML (stacked LSTM)

## Summary 

This project aims to justify the use of ML in stock price forecasting. The overall concept used is called stacked LSTM (Long Short Term Memory) in Deep Learning which is a branch of ML. By the help of python libraries the project aims to predict the price of a stock of 30 days. 

![image](https://user-images.githubusercontent.com/68069100/233975636-02584932-7b9e-488a-bed8-638cc1796d06.png)


* A practical approach based on theoretical understanding and not be used in live world. 

## Table of Contents 

* LSTM and Stacked LSTM 
* Tech stack 
* Python libraries used
* Output 

## LSTM and Stacked LSTM 

References to understand LSTM and Stacked LSTM :

1. [Understanding LSTM Networks by Colah's Blog](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
2. [Time series prediction with Deep Learning using Keras by Jason Brownlee](https://machinelearningmastery.com/time-series-prediction-with-deep-learning-in-python-with-keras/)
3. [Basic LSTM understanding](https://intellipaat.com/blog/what-is-lstm/#:~:text=LSTM%20Explained,-Now%2C%20let's%20understand&text=It%20is%20a%20variety%20of,data%20points%20such%20as%20images.)
4. [Stacked LSTM by Jason Brownlee](https://machinelearningmastery.com/stacked-long-short-term-memory-networks/)

## Tech Stack 

* Python and its libraries 

## Python libraries used

* Pandas DataReader
  This library is a helpful tool for importing finacial data into pandas dataframe and working with it in python. From the various interent sources Tiingo was opted. 

  - Tiingo : It is a tracing platform that provides a data api with historical end-to-end prices on stocks. API Key is generated. 
    [Read the documentation here](https://pandas-datareader.readthedocs.io/en/latest/remote_data.html#remote-data-wb)
    
    ![Screenshot (104)](https://user-images.githubusercontent.com/68069100/233987080-3df65bad-9518-4718-81e7-50ae57acc76c.png)

    
* Pandas: Used for working with datasets.
* Matplotlib: Visualization library. 
* NumPy: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. 
* Sklearn: Scikit-learn (Sklearn) is the most useful and robust library for machine learning in Python. It provides a selection of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistence interface in Python. This library, which is largely written in Python, is built upon NumPy, SciPy and Matplotlib.
* Tensorflow: It is used for implementing machine learning and deep learning applications. To develop and research on fascinating ideas on artificial intelligence, Google team created TensorFlow. TensorFlow is designed in Python programming language, hence it is considered an easy to understand framework.

Outputs

Close values of 'MS' i.e. Morgan Stanley

![output_22_1](https://user-images.githubusercontent.com/68069100/233987781-90fc4886-7273-4cfb-a6dc-8d31e604470a.png)

Close of values of 'MS' and 'JPM' compared 

![output_23_1](https://user-images.githubusercontent.com/68069100/233987905-1954c349-9073-44e3-b83d-7c172fea9ce2.png)

Train and test data predicted respectively as compared to the original data

![output_52_0](https://user-images.githubusercontent.com/68069100/233988033-4eb53be3-353a-489d-912d-e0601b0a3fa5.png)

Forecasted value for the next 30 days 

![output_64_1](https://user-images.githubusercontent.com/68069100/233988206-bb76f490-3249-4bc9-925b-ad4f8ad9aba9.png)

![output_65_1](https://user-images.githubusercontent.com/68069100/233988228-fe5e7dbd-121f-460c-98a9-7b59178a620f.png)

![output_67_1](https://user-images.githubusercontent.com/68069100/233988242-2e7c61e6-f0e2-475a-b42c-3679b9c3f0a4.png)
