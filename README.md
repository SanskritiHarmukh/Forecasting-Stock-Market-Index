# **Forecasting-Stock-Market-Index**



## Motivation and Purpose of the project

As we know Stock Market prices are highly unpredictable and volatile. This means that there are no consistent patterns in the data that allow one to model stock prices over time near-perfectly. So, as a stock buyer you can reasonably decide when to buy stocks and when to sell them to make a profit. Instead of considering it a stochatic or random process and that there is no hope for machine learning. We are trying to model the data, so that the predictions one make correlate with the actual behavior of the data.This is where time series modelling comes in. You need good machine learning models that can look at the history of a sequence of data and correctly predict what the future elements of the sequence are going to be.

## What does the project use?
We are working with Time Series Model, which analyzes a sequence of data points collected over a time interval. In time series analysis, analysts record data points at consistent intervals over a set period of time rather than just recording the data points intermittently or randomly. Time series data can be used for forecasting—predicting future data based on historical data.

## We are using 3 major open-source frameworks and tools in our project.

# Streamlit: The fastest way to build and share data apps


Streamlit is an open-source python framework for building web apps for Machine Learning and Data Science. We can develop and deploy our web app using Streamlit very easily. In just a few minutes you can build and deploy powerful data apps. 



# Prophet: Automatic Forecasting Procedure

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

# Yahoo Finance: To get free stock quotes 
Yahoo! Finance is a media property that is part of the Yahoo! network. It provides financial news, data and commentary including stock quotes, press releases, financial reports, and original content. It also offers some online tools for personal finance management.

## Python Installation and proceedings

**1.** Make sure you have python installed in your system already. If not, you can install it using in following command your terminal for installation
```
sudo apt install python:latest
```
 check version using,
 ```
 python3 --version
 ```
**2.**. Now, for installing and managing the software packages, we'll first install pip using 
```
sudo apt install python3.8 
```
and can check version by
```
pip3 --version
```
**3.** Next thing to do is create a virtual environment to separate your site packages used in this project from your rest of the projects, therefore to install use,
```
pip install virtualenv
```
create virtual environment using,
```
virtualenv <your_env_name>
```
and activate using,
```
source <your_env_name>/bin/activate
```
**4.** Further install all necessary modules using 
```
pip install streamlit fbprophet yfinance ploty
```
This will install all the required packages for the project such as, *numpy, pandas, matplotlib, etc.*

**Note** - Make sure you install one of the major dependency of Prophet `pystan` explicitly. You can refer [doc](https://facebook.github.io/prophet/docs/installation.html) for the same and if you encounter an import error with prophet then degrade `holidays` version to `0.9.12` and clone the [repository](https://github.com/facebook/prophet).

**5.** It's time to write some code. Refer the file attached in the repository for the same and understand the working of each line through the comments.

**6.** After writing the code, let's run it using the following command through the terminal
```
streamlit run home/username/Documents/<project_name.py>
```
The Streamlit app will now be visible in your browser at `localhost:8501`.

**7.** Lastly you can deactivate the virtual environment.

## Glimpse of the Web App
![image1](https://user-images.githubusercontent.com/74777863/142919488-f88c0ae3-fede-4f95-8241-20d1787bc82b.png)

![image2](https://user-images.githubusercontent.com/74777863/142919403-1c1c797b-4522-4ad8-97f2-6bfb466c2db7.png)

![image](https://user-images.githubusercontent.com/74777863/142919551-03a6b314-7b56-46d4-a882-410822095ba2.png)


Special Credits to [Patrick Loeber](https://github.com/python-engineer) and [video](https://youtu.be/0E_31WqVzCY) for stock prediction.

Collaborators and Team Members [Mansi Mishra](https://github.com/0904-mansi) | [Satyam Jain]() | [Archit Chawda]()


Made with ♥️.


