# Customer-Churn-Analysis
Analyzing customer churn for a subscription-based streaming service
# Project Background
StreamLinx is a company established in 2016. It offers streaming service for Movies via its Website and Mobile App. The company collects vasts amount of data ranging from sales, product offerings, marketing efforts and operational efficicency. This project analyzes and sythensizes the subscription data with the main focus on reducing churn of customers to ensure the success of StreamLinx together with developing proactive retention strategies, personalized engagement tactics, and improved service offerings.
## Insights and Recommedations are provides from the follwoing key areas:
- Subscriber Trend Analysis: Analyze historical subscriber data to identify patterns and trends related to churn.
- Factors Leading to Churn:  Determine key factors influencing customer churn decisions.
- Customer Segmentation: Create customer segments based on churn risk profiles.
- Retention Strategies:  Recommended actionable retention strategies for different customer segments
The PowerBi dashboard can be found here.
The SQL Queries utilized to perform the analysis can be found here.
# Data Structure and Overview 
The dataset contains information about subscribers, their viewing habits, account details, and churn status. Below is a detailed description of the available features:
Column Name	Description	Data Type
User_ID	Unique identifier for the subscriber	String
Subscription_Type	Category of subscription (Free Trial, Basic, Standard, Premium)	Categorical
Join_Date	Date when the user subscribed to the service	Date
Churn_Flag	Binary indicator if the user has churned (1) or not (0)	Binary
Age	Age of the subscriber	Numeric
Gender	Gender of the subscriber (M/F/Other)	Categorical
Monthly_Viewing_Hours	Average watch time per month	Numeric
Genres_Watched	Count of different genres watched	Numeric
Support_Tickets	Number of support queries raised by the user	Numeric
Discount_Used	Whether a discount was used at sign-up (Yes/No)	Binary
Payment_Method	Payment option selected (Credit Card, PayPal, Mobile Money)	Categorical
Auto_Renew_Enabled	Whether automatic renewal is enabled (Yes/No)	Binary
Last_Login_Date	Date of the user's most recent activity	Date
Number_of_Devices	Count of devices linked to the account	Numeric
# Executive Summary
