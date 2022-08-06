# Time-series-analysis---predicting-stock-prices-DSP-project


Time series analysis - it is the way of studying the characteristics of the response variable with respect to time, as the independent variable, to estimate the target variable as the point of reference.

<br/>The usage of time series models is twofold:
1.	Obtain an understanding of the underlying forces and structure that produced the observed data
2.	Fit a model and proceed to forecasting, monitoring or even feedback and feedforward control.
Time-series analysis (predicting the future values) this is a major part of study in the field of data science and machine learning but here we will see how we can deal with this problem in a [non-conventional](https://towardsdatascience.com/adaptive-filtering-in-stock-market-prediction-2db9ad7ae7f9) approach. Adaptive Filtering.

<br/> Adaptive filters – The goal is to estimate a signal y from a signal x. An adaptive filter is an adjustable filter that processes in time x. The output of the filter is the estimator y ̂ of y. The filter is adjusted after each time step to improve the estimation <br/>

![image](https://user-images.githubusercontent.com/64704390/183240479-e1445968-92c0-4c01-a95d-fb49ef8b8d4b.png)
                                                                                                                                                                              <br/> [Source](https://www.mathworks.com/help/dsp/ug/overview-of-adaptive-filters-and-applications.html)                                                                 <br/> Before proceeding to the next part, (i.e) the code I urge you to read and get a basic understanding about what adaptive filters are what a LMS adaptive filter is <br/>
For the project I'm taking the stock prices of [Mahindra and Mahindra](https://finance.yahoo.com/quote/M%26M.NS/history). The project is done implemented using python with the help of simple libraries - [NumPy](https://numpy.org/doc/), [Matplotlib](https://matplotlib.org/stable/index.html), [Pandas](https://pandas.pydata.org/docs/user_guide/index.html#user-guide). I would recommed you to familiarise yourself with the basic syntaxs of these libraries.<br/>
You may have to tweak the filter order; learning rate and other parameters if the filter doesn't adapt to your dataset.
   
