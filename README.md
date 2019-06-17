# Analyze_AB_Test_Result_DAND
Goal of this project is to understand the results of an A/B test run by an e-commerce website. 
***
### Overview
This project is one of Udacity's interesting Data Analyst Nano Degree project. in this project a fictitious company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Our goal was to work through a notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

***
### Contents
* Introduction
* Part I - Probability
* Part II - A/B Test
* Part III - Regression

***
I created a regression model to test for impact of countries on conversion. I also tested to see if time of day and day of week had any impact on conversion. 

***
### Conclusion 
* Using different methodology in part II and part III, p-value changed, but in either case, we fail to reject the null as value is still higher than alpha.
* Based on this analysis, there is no practical significance in rolling out the new page over old page. Conversion rate for old page is better than the new page, albeit not by a lot.
* Comparing users among different countries also doesn't show considerable difference in conversion.
* In trying to determine the effect of time on the conversion we used the day of the week and the period of the day as categorical variables and we say that generally these variables had little to no effect on conversion except for the interaction between saturday and monday and the page groups. For these two variables they seemed to show a negative effect on conversion relative to Tuesday which was our refrence category.
* Lastly, binning the timestamps into periods might have resulted in loss of information. To test this, further analysis can be carried out using the hours of the day as dummy varibles.[4]
> **consideration: 
These inferences are strictly based on data on hand. This analysis acknowledges its limitations due to factors not included in the data.**
