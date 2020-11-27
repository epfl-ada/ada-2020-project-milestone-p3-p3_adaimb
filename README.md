# ada-2020-project-milestone-p3-p3_adaimb

**1. Title: Predicting the present with google trends**

**2. Abstract :**

We would like to add some figures to the existing paper. The first figure we would want to add is the same as Figure 2 but for the initial claims data set. Then we could do same kind of prediction for the same dataset (initial claims) but for another time series (for example 2011 to 2020). Those figures would allow us to further check the accuracy of the trend model and would support or not the theory of the authors. Furthermore, we can perform this forecasting method to another dataset. One which came to our mind is Exchange Rate forecasting. Indeed, publicly available tool Google Trends could help us to predict the U.S. / Euro Foreign Exchange Rate. We will perform the same seasonal autoregressive model and see if google trends validates improves the model.


**3. Research questions :**

**Q1**

Does the model improve the prediction over the base model for the initial claims data ?

**Q2**

Is the model consistent with other topics and/or other time series ?

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

Perform a seasonal autoregressive model on the initial claims dataset between 2007 and 2011 (base model) and then do the same with trends features. Compute the overall MAE and the MAE during the four periods described in Table 1 as turning points. 

**Q2**

Perform a seasonal autoregressive model on the initial claims dataset between 2011 and 2020 (base model) and then do the same with trends features. Compute the overall MAE.

**Q3**

Perform a seasonal autoregressive model on the exchange rate dataset between 2004 and 2011 (base model) and then do the same with trends features *Euro/Dollar, Inflation and Prices*. Compute the overall MAE.


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

Victoria: builds the model and compute accuracy 

David: makes the figures 

Anastassia: Interpretation of the results 

**Week 2:** 

Victoria: Interpretation of the results 

David: builds the model and compute accuracy 

Anastassia: makes the figures

**Week 3:** 

All: write the report 

  
