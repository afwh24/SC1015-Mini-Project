# ***SC1015-Mini-Project (FCSG TEAM 2)***
**Team Members:**
1. Alfred Fong Wei Hao
2. Boo Wen Jun
3. Alan Yip Boon Tiong

# **Our Motivation** <br> 
Back in 2014, there were 1 billion smartphone users. Now, the number is nearly 5 billion, a 5x increase and forecasted to reach 6 billion by 2027. This shows the sales potential for smartphones is boundless. <br> <br> 
Therefore, our aim is to utilise data analysis and machine learning to provide actionable insights for manufacturers and retailers to focus on attributes that enhance sales performance in India.<br> 


# **Problem Statement** <br>
To analyze how the selling price of smartphones is influenced by their brand, memory RAM, storage space, and phone ratings and to create a predictive model that can accurately estimate a smartphone's market value based on these features (in India) </br>

# **Dataset Information** <br>
**Data Source: https://www.kaggle.com/datasets/yaminh/smartphone-sale-dataset** <br> 
1. The dataset we are using is India smartphone sales data from Kaggle with a score of 8.82 for usability. <br>
2. It offers an overview of the smartphone market, enabling analysis of pricing strategies, consumer preferences, and market trends in India. 


# **Our Data Models** <br>
**Disclaimer: Some of the models take some time to train during execution**
 <br><br>
 **More details and information are explained in our video presentation submission**
 <br><br>
**Linear Regression Model (Uni-variate)**
1. Performed uni-variate linear regression with memory RAM, storage, rating as predictor and original price as the response
2. Poor goodness of fit
   
**Linear Regression Model (Multi-variate)**
1. Performed multi-variate linear regression to uncover relationships and dependencies that are not evident in a univariate model
2. Have a better goodness of fit as compared to the uni-variate linear regression model
   
**Classification Trees**
1. Classification trees give us a better understand the non-linear relationships and interactions between variables
2. Captures non-linear relationships between variables more effecitvely than a linear regression model
3. Performed One-Hot Encoding (OHE)
4. Performed Random Forest
5. Performed Grid Search

**Neural Network**
1. Learn intricate patterns and non-linear relationships between data
2. Useful in extracting features and hierarchies, providing insights into complex data structures
3. Leading to a better goodness of fit and higher predictive accuracy compared to other models


# **References** <br>
1. Smartphone usage statistics for 2024 (surprising). Backlinko. (2024, March 13). https://backlinko.com/smartphone-usage-statistics 
