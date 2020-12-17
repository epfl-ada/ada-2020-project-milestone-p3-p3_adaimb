# ada-2020-project-milestone-p3-p3_adaimb

**1. Title: Predicting the present with google trends**

**2. Abstract :**

We would like to add some figures to the existing paper. The first figure we would want to add is the same as Figure 2 but for the initial claims data set. Then we could do same kind of prediction for the same dataset (initial claims) but for another time series (for example 2011 to 2020). Those figures would allow us to further check the accuracy of the trend model and would support or not the theory of the authors. Furthermore, we can perform this forecasting method to another dataset. We came across several fitted options of datasets but the one in which we were the most interested in was the Exchange Rate forecasting dataset. Indeed, publicly available tool Google Trends could help us to predict the U.S. / Euro Foreign Exchange Rate. We will perform the same seasonal autoregressive model and see if google trends validates improves the model.



**3. Research questions :**

**Q1**

How can we improve the prediction model Google Trends using? Which parameters have a significant impact on the prediction?

**Q2**

Is the model consistent with other time series ? Is the model accurate when we try to perform out-of-sample forecasting?

**Q3**

Has Google Trends the power to help us predict one-month-ahead movements of the USD/EUR rate.

**4. Proposed datasets :**

**Q1**

Initial claims for unemployment benefits given by the TAs for p2 (merged_iclaims.csv)

**Q2**

a) Trends *Jobs* and *Unemployment* from 2004 to today: https://trends.google.com/trends/explore?date=all&geo=US&q=Jobs,%2Fm%2F07s_c

b) Unemployment Insurance Weekly Claims Data : https://fred.stlouisfed.org/series/ICSA


**Q3**

a) Exchange Foreign Rate  Japan/Us: https://fred.stlouisfed.org/series/EXUSEU

b) Trend data (*Euro/Dollar*, *Inflation*, *Prices*):https://trends.google.com/trends/explore?date=all&geo=US&q=Inflation,Prix,%2Fg%2F122jqk1s
We chose them basing us on the following paper (*Google Trends and the forecasting performance of exchange rate models*, https://onlinelibrary.wiley.com/doi/full/10.1002/for.2500?saml_referrer)

 **5.Methods**

**Q1**

Perform a seasonal autoregressive model on the initial claims dataset between 2007 and 2011 (base model) and then do the same with trends features. Compute the overall MAE and the MAE during the four periods described in Table 1 as turning points. Perform parameters selections for the number of lag terms and the size of the training set in order to see what improves the forecasting. 

**Q2**

Perform a seasonal autoregressive model on the initial claims dataset between 2011 and 2020 (base model) and then do the same with trends features. Compute the overall MAE. Perform out-of-sample forecasting to predict what happened in 2020 training the model over 2011-2019. Add another trend (Covid-19) to see if it improves the prediction. 

**Q3**

Perform a seasonal autoregressive model on the exchange rate dataset between 2004 and 2011 (base model) and then do the same with trends features *Euro/Dollar, Inflation and Prices*. Compute the overall MAE, and analyze more in detail the impact of Google trends on the prediction of the recession periods, and see how can we improve it.


 **Proposed timeline**

**Week 1 (Nov. 30th to Dec. 6th)**

Questions 1 and 2. Seasonal autoregressive model on the initial claims dataset
Results interpretation and figure.

**Week 2 (Dec. 7th to Dec. 13th)** 

Question 3. Seasonal autoregressive model on the exchange rate dataset. 
Results interpretation and figure. 

**Week 3 (Dec 14th to Dec 18th)**

Write the report and the pitch for the video. Make conclusions. 


**Organization within the team**

**Week 1:** 

David started the question 1 and 2 as the data collection. We all three realized the replication of Figure 1 of our paper, and we rethank about the questions that would lead our project to be more precise on what we want to do. 

**Week 2:** 

Victoria focused on finishing and interpreting the results of questions 1 and 2. David and Anastassia answered to the question 3 and made the data vizualisation. 

**Week 3:** 

Building of the website with the data story, finish the details in the notebook. Write the pitch for the video and make the video. 

  
