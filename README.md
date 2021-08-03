# Web-Scraping-and-Data-Analysis-on-OYO-Hotel-Rooms
## Steps Involved

* Identify the URL from which you need the data.
* Inspect the HTML code behind the page.
* Find the elements you want to extract.
* Write the code the store the data in the required format.


## Life Cycle of the Data Analyst Project:

*  1) Business Understanding (Understand the Business functionalities beofore we go furthur)
*  2) Data Requirement (Should know important variables)
*  3) Data Collection(We Use Web Scraping)
*  4) Data Cleaning ( Missing Data, Pre processing) 
*  5) Data Analysis (EDA) to know insight about data 

## Problem statement :
  Based on my analysis, I want to show which is the budgetfriendly city with all features to book OYO Rooms.

##  I have shown the data acoording to this questions in Univariate Analysis ,Bivariate and Multivariate Analysis!!
* Which is the highest Review?
* Where the Offer_Percentage maximum density?
* Where the Offer_Price maximum density?
* Where the Original_Price maximum density?
* Where the Rating maximum density?
* what is the peak point of Offer_Percentage by using KDE plot?
* what is the AC_Availability count?
* what is the Wifi_Availability count?
* At what percentage the Offer_Percentage count is maximum ?
* Which Rating has maximum count?
* In which city the Original_Price is maximum?
* What is the variation between Offer_Percentage and Original_Price by using line plot?
* What is the variation between Offer_Percentage and Original_Price by using reg plot?
* What is the variation between Offer_Price and Rating by using reg plot?
* How is the Wifi_Availability according to Original_Price by using Box plot to analise the outlayers ?
* How is the Wifi_Availability according to Offer_Price by using Box plot to analise the outlayers ?
* What is the Relation between Reviews and Wifi_Availability by using crosstab ?
* what is the Realtion between City_Name and AC_Availability by using crosstab ?
* what is the Realtion between City_Name and Wifi_Availability by using crosstab ?
* what is the Realtion between Offer_Percentage and City_Name by using crosstab ?
* I have group the data for Offer_Price and City_Name where the Offer_Price is minimum ?
* I have group the data for Offer_Price and City_Name where the Offer_Price is maximum ?
* On the basis of City_Name I have shown the analysis for all the columns by using pair plot?
* I have shown subplots for Wifi_Availability by using countplot and for Rating and Offer_Percentage by using   boxplot and for all the columns by using heatmap of correlation and for Offer_Percentage and Wifi_Availability  by using scatter plot  


## Libraries imported for this project
* import warnings
* warnings.filterwarnings('ignore')
* import numpy as np
* import pandas as pd
* import matplotlib.pyplot as plt
* import seaborn as sns
* import requests
* from bs4 import BeautifulSoup
* import re
* import time
* from IPython.core.interactiveshell import InteractiveShell
* InteractiveShell.ast_node_interactivity = 'all'
## Conclusion:
  According to  my analysis based on all the graphs the city Banglore is referred as good than compared to city Hyderabad and Mumbai to book OYO hotel rooms.
