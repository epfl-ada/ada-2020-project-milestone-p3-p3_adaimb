# ada-2020-project-milestone-p3-p3_adaimb

**1. Title: Predicting the present with google trends**

**2. Abstract :**

We would like to add some figures to the existing paper. The first figure we would want to add is the same as Figure 2 but for the initial claims data set. Then we could do same kind of prediction for the same dataset (initial claims) but for another time series (for example 2011 to 2020). Those figures would allow us to further check the accuracy of the trend model and would support or not the theory of the authors. Furthermore, we can perform this forecasting method to another dataset. One which came to our mind is birth rate forecasting. Indeed, it is common knowledge that it is influenced by multiple indicators of the well-being in societies and this could be reflected by google trends. We will perform the same seasonal autoregressive model and see if google trends validates improves the model.


**3. Research questions :**

**Q1**

Does the model improve the prediction over the base model for the initial claims data ?

**Q2**

Is the model consistent with other topics and/or other time series ?

**Q3**

Does a drop in fertility follows the recession of 2008? In general when did fertility increased or dropped specifically ? 

**4. Proposed datasets :**

**Q1**

Initial claims for unemployment benefits given by the TAs for p2 (merged_iclaims.csv)

**Q2**

a) Trends *Jobs* and *Unemployment* from 2004 to today: https://trends.google.com/trends/explore?date=all&geo=US&q=Jobs,%2Fm%2F07s_c

b) Unemployment Insurance Weekly Claims Data : https://fred.stlouisfed.org/series/ICSA


**Q3**

a) Birth data in the US : https://www.cdc.gov/nchs/data_access/Vitalstatsonline.htm?fbclid=IwAR0bH9Qg3sLpoXo9zs69ufGX9p2YflQNJ7Ge9L1NwY_Uwb-AEYsT3WHua5U 

b) Trend data for the modeling of the birth rates in the US (*pregnancy*, *maternity*, *ovulation*): https://www.cdc.gov/nchs/data_access/Vitalstatsonline.htm?fbclid=IwAR0bH9Qg3sLpoXo9zs69ufGX9p2YflQNJ7Ge9L1NwY_Uwb-AEYsT3WHua5U
 
 **5.Methods**

**Q1**

Perform a seasonal autoregressive model on the initial claims dataset between 2007 and 2011 (base model) and then do the same with trends features. Compute the overall MAE and the MAE during the four periods described in Table 1 as turning points. 

**Q2**
Perform a seasonal autoregressive model on the initial claims dataset between 20012 and 2020 (base model) and then do the same with trends features. Compute the overall MAE.

**Q3**
Perform a seasonal autoregressive model on the birht rate dataset between 2004 and 2011 (base model) and then do the same with trends features *pregnancy, maternity and ovulation*. Compute the overall MAE and interpret the results.


 **Proposed timeline**

Week 1 (Nov. 30th to Dec. 6th)

Questions 1 and 2. Seasonal autoregressive model on the initial claims dataset
Results interpretation and figure.

Week 2 (Dec. 7th to Dec. 13th) 

Question 3. Seasonal autoregressive model on the exchange rate dataset. 
Results interpretation and figure. 

Week 3 (Dec 14th to Dec 18th)

Write the report and the pitch for the video. Make conclusions. 


**Organization within the team**

Week 1: 

Victoria: builds the model and compute accuracy 

David: makes the figures 

Anastassia: Interpretation of the results 

Week 2: 

Victoria: Interpretation of the results 

David: builds the model and compute accuracy 

Anastassia: makes the figures

Week 3: 

All: write the report 

  
