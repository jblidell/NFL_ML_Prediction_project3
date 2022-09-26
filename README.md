# Using NFL Data to make predictions

## A look at how EPA (Estimated Points Added) can be utilized to predict
game outcomes.

Play-by-play data for 2022 season as data source
- Python used for general data processing
- ML algorithms used to make predictions
  - Logistic Regression
  - Bagging Classifier

 The class presentation is located here **File:** [Presentation of the EPA and ML Presentation](./SMU Team #2.pdf)

## Table of Contents
1. [Front-end Interface](#1-Front-end-Interface)

2. [Calculate and Plot the output from the CLI.](#2-Calculate-and-Plot-the-output-from-the-CLI)

3. [Simulation Trajectories.](#3-Simulation-Trajectories)

4. [Back-End Functionality.](#4-Back-End-Functionality)

5. [Compose the data story.](#5-compose-the-data-story)

---

## 1. Front-end Interface

![1](./Images/Recording%202022-06-08%20at%2020.20.03.gif)

* The CLI python script is located here **File:** [Crypto Porfolio CLI](/appy2.py)
* If then statement was built to personlize the type of investment to user wanted
    
  

## 2. Calculate and Plot the output from the CLI

* The output python script is located here **File:** [Crypto Results Porfolio](/results.py)

 ![2](./Images/Screen%20Shot%202022-06-09%20at%201.46.14%20PM.png))
* API used on this project are as follows
   * `yfinance`
   * `sqlalchemy`
   * `requests`
   * `datetime`
   * `statistics` 
   
* The website used for gather crypto data
   * alternative
   
* Create a new DataFrame named `stocks_dataframe` by creating these columns and display the appropiate date.
   * `Coins`	
   * `Symbol`	
   * `Category`	
   * `Price`	
   * `24Hr Volume`
   * `Market Caplization`	
   * `1hr % Change`	
   * `24hrs %Change`	
   * `7days %Change`	
   * `Sharpe Ratio`	
   * `Variance`
   
* Bar chart was created with predetermined currencies 
* The % this portfolio has made within 1 year period
* The line graph that shows how much money that would have been made if the user invested 1 year prior


## 3. Simulation Trajectories

* The output python script is located here **File:** [MC Database](.//mc_database.ipynb)

These clips demonstrate the simulator running on our pre-selected portfolio data.
Careful usage of this functionality can enhance our users ability to make informed long term portfolio selections.

![3](./Images/MC-low_risk.gif)

---

![4](./Images/MC-Plot.gif)

---



## 4. Back-End Functionality

![5](./Images/Low_Risk_Portfolio.png)
![6](./Images/Screen%20Shot%202022-06-09%20at%204.40.23%20PM.png)

The following portions of code demonstrate how we use historical data to project possible portfolio returns.

## 5. Compose the Data Story

We are giving the average person the opportunity to invest into cryptocurrency without the high-risk crypto is associated with. Our portfolios are designed to minimize long-term risk while benefiting from the accumulated growth of Bitcoin, Ethereum, Litecoin, and other leading cryptocurrencies.
Tired of hearing about stocks that already made investors a lot of money? Our Crypto Porfolio Advisor picks top value stocks with strong long-term growth potential.

Utilizing real-time data users will have access to their own personal crypto advisor at the palm of their hands, or on their computer.

## Contributors
Michael Morton, Jarrett Lidell, Daniel Boyne, and Severo Fernandez
