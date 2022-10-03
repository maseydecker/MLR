# Multiple Linear Regression Analysis of Real Estate Data

## Research Question
 
The process of selling a home can be a difficult journey. This is especially true when it comes to the valuation process. Often, the real estate agent comes to the house and after much head scratching, makes an evaluation on the home without much quantitative insight. This can be frustrating to the owners of the homes, the brokerage, and the real estate agent when either the house won’t sell, or the house down the street with the same specs sells for a much larger sum. The question this research paper will answer is, can a multiple linear regression model be constructed that predicts the best. Sales price for a home?

The contribution of this study to the field of Data Analytics and the MSDA program is to create a predictive model which can estimate the valuation of a home in California. This will ensure that the company does not need to gather all data regarding home prices in the area to make a valuation on a home. With all of the houses for sale out there across the county, it would be impossible to have a sure knowledge of the real estate market, but regression analysis allows for an on-market valuation (Barr, 2018). Valkov (2021) shows that a model can be created to predict home prices using multiple linear regression and that is the hypothesis of this study.


## Data Collection

The data needed to answer this question is a publicly available dataset from Kaggle. According to Uslu (2022), “the vast majority of Kaggle datasets are reliable.”
https://www.kaggle.com/datasets/yellowj4acket/real-estate-california
The dataset contains the real estate listings for the state of California for the first 6 months of 2021. The data contains 35,390 rows of data and 39 columns. The independent variable from the data is the price of the house and the dependent variables include the rest.

The advantages of this dataset is that it is very easily accessible to anyone as it is a public dataset. As stated before in this section, Kaggle datasets are pretty reliable. The data is already gathered and aggregated in such a way that it will make analysis of the dataset almost immediate. There are also some disadvantages to this dataset. As the data is already gathered, it impedes the ability for the researcher to choose which observations are most relevant to answering the research question. With the dataset being public, there is also the potential that the data may not be accurate or complete.

Usually, a researcher will decide on a research question and then gather the relevant data to answer this research question. In this study, the data is already gathered and then a research question was created based on the data. To overcome this challenge, the data will be thoroughly reviewed to come to a complete understanding of the observations therein. The data will also be cleaned and prepared before the analysis takes place.


## Data Summary and Implications

This analysis started with the question: Can a multiple linear regression model be constructed that predicts the best sales price for a home? The hypothesis was that a model could be constructed that predicts the best sales price for a home. After preparing the data for the analysis and creating the model, we can reject the null hypothesis and answer the research question with yes, a model can be constructed that predicts the best sales price for a home. This is determined by the r-squared value of the model which was 0.212. This indicates that the model explains for 21.2% of the variance in the target variable or price of a home. This also indicates that there are other factors influencing the sales price of a home which are not included in the model. Nonetheless, the model allows for a reasonable estimate of the valuation of a home.

As stated previously in this research paper, the analysis was limited by the accuracy and completeness of the data. While there is no indication that the data is not accurate, it is a publicly available dataset and was gathered by observations from someone outside of this analysis and therefore, the accuracy cannot be completely confirmed. 

This model can be a great tool for making a statistically backed decision on the valuation of a home. It would be recommended for realtors and brokerages within California to use this model to determine the sales price of a home being put on the market. It can also be used by individuals looking to sale their homes themselves or wanting to ensure their realtor made the best valuation on the home.

There are many different approaches for future study of this data set. One way this data set could be used is to create a time series forecast of home prices. This would give a good indication to where home prices are expected to go in the future. An ARIMA model could be used to make some short-term predictions on the prices of homes. This would be helpful in letting home sellers know the best time to sell their homes at a better valuation. Another approach would be to do a cluster analysis on the home prices. Real estate can be much different across a state or even a city. A cluster analysis would help to identify patterns in the data and determine which areas have the highest or lowest valuations.
![image](https://user-images.githubusercontent.com/111837210/193497619-906f7ba8-8732-4d41-9de8-4bea6f85c47e.png)



