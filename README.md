# Project Background
This project analyzes customer churn by identifying the key factors influencing churn across different customer segments, including geography, gender, age group, tenure, credit score, and product ownership. The analysis helps identify key churn drivers and supports data-driven customer retention strategies.

Insights and recommendations are provided on the following key areas:

 • **Churn Analysis:** Evaluated churn patterns across multiple segments to identify customers likely to leave the bank.
 
 • **Customer Analysis:** Analyzed customer behaiour and customer patterns across different Geography, Age Group and Gender. To identify 
    high risk customer segments.

 • **Revenue Analysis:** Analyzed Estimated Bank Revenue across different Geography, Gender And Number of Products. To understand revenue 
    contribution across different customer segments. 

# Data Structure & Initial Checks
 The Bank database consists of two tables: customer_info and account_info. For analysis, I created a final merged table (bank_churn)  
 containing 10,000 customer records, which was used for all SQL analysis and Power BI dashboards.

![image alt ](https://github.com/itsankit018/bank_customer_churn_analysis/blob/ac4076b74a50219e410e87352a867d319be1da06/Bank%20DataBase%20Structure%20(ERD).png)


# Executive Summary
**Overview of Findings**
  The Bank serve 10,000 customers from that 2038 have churned, that resulting in a customer churn rate upto 20.38(%). 
  In bank the Current  Active customers are 4415 and Inactive customers are 3547. The following analysis identifies the key factors  influencing customers churn and highlight opportunities to imporve customer retention.

![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/e94140097ec0a3d2fbfbc8704dfe8f3208ca71ae/executive%20dashboard.png)

**Churn Analysis**

  **Customer by Geography:** In region the geography has the highest churn rate. The chart shows that Germany at 32(%), highest churn rate.  Customers are in Germany are more likely to leave, so Marketing should focus on that region.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/main/Churn%20Customer%20By%20Geography.png)

**Customer Churn By Age Group:** This insight shows that the Customers between 46-60 are more likely to leave the bank. The chart shows that Middle Age segment has highest churn rate upto 51.12(%).The Bank should focus on retaining the middled-age customers.
 
 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20BY%20Age%20Group%20.png)
 
**Customer Churn By Gender:** What I find here in Gender semgent Female customers have a hihgher churn rate rather than Male customers.
The chart shows that Female Customer churn rates are 25.09(%) and the Male customers churn rates are 16.46(%).The Bank should investigate why female customers are leaving more frequently as compared to Male customers.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Gender.png)

**Customer Churn By Member Status:** The customer who are not active has highest churn rate. According to analysis that the customers who are not member records the highest churn rate 26.85(%). This suggests that Bank more focus to re-engaging inactive customers as they are more likey to leave the bank.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Member%20Status.png)

**Customer Churn By Tenure Segment:** What I Find here the new customers and our more long term customers shows the highest customers churn rate. The data shows that New customer has the highest churn rate 21.38(%) and the second largest is Long term customers. This indicates that Bank should focus on retaining customer beacuase they have highest churn rate and for Long term customers should also be investigate because losing loyal customer can effect the Bank revenue or can effect on long term profitabilty.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Tenure%20Segmet.png)


**Customer Churn By Credit Score Segment:** Customers in the SUB-PRIME segment slightly shows highest churn rate other credit score segment.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Credit%20Segment.png)


# Customer Analysis Summary
**High Value Customers By Geography:** France has Highest valuable customers, second highest is Spain and then Germany. 
According to analysis:
  **France:** 420 Valuable Customers.
  **Spain:** 186 Valuable Customers.
  **Germany:** 160 Valuable Customers.
This bank should retain high-value customers in France through personalzied offers and loyalty program. While increasing high-value customers in Spain and Germany through targeted marketing campaigns.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/4e17c8ecf3189b678f2a1654c5c99948ad530235/High%20value%20customers%20By%20Geography.png)

 **Customer Churn By Age Group:** This insight shows that the Customers between 46-60 are more likely to leave the bank. The chart shows that Middle Age segment has highest churn rate upto 51.12(%).The Bank should focus on retaining the middled-age customers.
 
 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20BY%20Age%20Group%20.png)

 **Retention Rate VS Customer Churn:** Customer retention is significantly higher than the customer churn rate. The visualization shows that Retention Rate(%) is 79.62%, while churn rate is 20.38%. The most customer are retained the Bank should focus on reducing churn by targeting high risk customers segments.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/ef1770638956ab6efa72a58804e7d8725a665ffe/Retention%20Rate%20VS%20Customer%20Churn%20Rate.png)

**Customer Churn By Age Group:** This insight shows that the Customers between 46-60 are more likely to leave the bank. The chart shows that Middle Age segment has highest churn rate upto 51.12(%).The Bank should focus on retaining the middled-age customers.
 
 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20BY%20Age%20Group%20.png)
 
**Current Active Users VS Total Churn BY Geography:** France, Spain has the highest current Active customers, while Germany has the Lowest Active users. Based on the analysis:
  **France:** 2293 Active Customers & 810 leave the Bank.
  **Spain:** 1170 Active customers & 414 leave the Bank.
  **Germany:** 952 Active Customers & 814 leave the Bank.
This indicates that Germany Bank requires that Germany Bank requires immediate attention as it has relatively fewer Active Customers and Number of churn custoemrs. Further analysis by Gender, Age Group and Tenure can help to identify which customer segments are mostly likely to leave the Bank.
![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/main/Current%20Active%20Customers%20Vs%20Total%20customer%20churn.png)
    
    
# Financial Analysis
**Net Margin By Geography:** France stands out with highest Net Margin among all region. The data shows that France has highest Net Revenue income:
    **France:** 35M
    **Spain:** 17M
    **Germany:** 10M.
 The visualization shows that France is actually covering our Bank Persona and in other regions like Spain and Germany the Bank should run loyalty program or engage with Non-Active users to increase revenue.

<p align="center">
  <img src="https://github.com/itsankit018/bank_customer_churn_analysis/blob/main/Current%20Active%20Customers%20Vs%20Total%20customer%20churn.png" width="750">
</p>
      
**Credit Card Revenue By Gender:** As per analysis in Gender the Male customers generating higher revenue in credit card segment as compared to Female customers.
      **Male Revenue:** 905k
      **Female Revenue:** 657k.
The Bank should analyze why Male customers generating more revenue and apply the same stratigies to increase more revenue like introduced personalized offers to increase revenue for Female customers.
        
**Net Revenue By Gender:** According to the analysis Male customers stands out with highest revenue as compared to Female customers.The insight shows:
        **Male Customers:** 33.33M
        **Female Customers:** 28.52M
The Male and Female customers dosen't have such huge difference from Females through running campaigns, offers and cross selling opportunities.

**Net Revenue By Age Group:** Based on the analysis Adult has generated highest Revenue among all other Age-Group. The data shows:
        **Adult:** 37M
        **Young-Adult:** 13M
        **Middle-Age:** 10M
        **Senior:** 3M
The Adult Age-Group generated significant revenue but the Bank should focus on Young-Adult, Middle-Age, Senior to generate more revenue using marketing like low-interest loans, Card benifits, targeted marketing campaign.

**Net Revenue By Age Group:** Product 1 and Product 2 shows the highest revenue on other side products 3 and 4 showed the weakest persformance. The data shows:
        **Product 1:** 26M
        **Product 2:** 34M
        **Product 3:** 2M
        **Prodcut 4:** 0M
The data indicates that Product 1 and Product 2 performing well but Bank should focus on customer demand, target promotion and improve products to increase revenue in these products.



   

      



 
