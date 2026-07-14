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

  **Customer by Geography**:In region the geography has the highest churn rate. The chart shows that Germany at 32(%), highest churn rate.  Customers are in Germany are more likely to leave, so Marketing should focus on that region.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/main/Churn%20Customer%20By%20Geography.png)

**Customer Churn By Age Group**:This insight shows that the Customers between 46-60 are more likely to leave the bank. The chart shows that Middle Age segment has highest churn rate upto 51.12(%).The Bank should focus on retaining the middled-age customers.
 
 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20BY%20Age%20Group%20.png)
 
**Customer Churn By Gender:What I find here in Gender semgent Female customers have a hihgher churn rate rather than Male customers.
The chart shows that Female Customer churn rates are 25.09(%) and the Male customers churn rates are 16.46(%).The Bank should investigate why female customers are leaving more frequently as compared to Male customers.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Gender.png)

**Customer Churn By Member Status: The customer who are not active has highest churn rate. According to analysis that the customers who are not member records the highest churn rate 26.85(%). This suggests that Bank more focus to re-engaging inactive customers as they are more likey to leave the bank.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Member%20Status.png)

**Customer Churn By Tenure Segment**: What I Find here the new customer and our more long term customers shows the highest customer churn rate. The data shows that New customer has the highest churn rate 21.38(%) and the second largest is Long term customers. This indicates that Bank should focus on retaining custoemr beacuase they have highest churn rate and for Long term customers should also be investigate because losing loyal customer can effect the Bank revenue or can effect on long term profitabilty.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Tenure%20Segmet.png)


**Customer Churn By Credit Score Segment**:Customers in the SUB-PRIME segment slightly shows highest churn rate other credit score segment.

 ![image alt](https://github.com/itsankit018/bank_customer_churn_analysis/blob/fa4311017a03d8790105687c493b11622844876d/Churn%20Customer%20By%20Credit%20Segment.png)



 


 
