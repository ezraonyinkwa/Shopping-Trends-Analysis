# Shopping-Trends-Analysis-Power-BI


### Project Overview

In today's competitive retail landscape, understanding hopping trends is crucial for business to stay ahead. This report  delves into a comprehensive analysis of shopping trends, examining various aspects such as customer behaviour, product preferences and regional differences. Our goal i to provide actionable insights that can help business optimize their strategy and enhance customer satisfaction.

### Data Sources
The dataset was sourced from [kaggle](https://www.kaggle.com/datasets/riturajpradhan/shopping-trends).This dataset 'Shopping Trends Data  contails detailed shopping trends , it includes vital information on customer demographics, purchasing behaviour and product specifics enable a comprehensive analysis of shopping trends.

### Tools Used
-  Microsoft Excel -Data cleaning
-  Microsoft Power BI -Data visualization

### Skills 
- Data Cleaning
- Power Query
- Data Modelling
- Data Analysis EXpression (DAX)
- Data Visualization

### Data Cleaning/Preparation
In the intitial data preparation phase, we performed the following tasks;

1. Data Formatting

   We carried out data formatting  dataset by ensuring the letters were well capitalised by using the function =PROPER().
   We formatted the data by replacing values to a more understandable and easy format (This was carried out in the size column), we used the find and replace option to carry out this formatting.

2. Handling Missing Values

 We ran a quick check for any missing values using ctrl+G to check for blanks,the dataset contained no missing values.

3.Removing Duplicates
We checked for duplicates value by highlighting the wholee data and pressing ctrl+G but there were no duplicates found.

### Data Moddelling
Out of the fact taable we created three other tables mainly; Customer Table,Product Table and Regional Table. The primary key was Customer ID.
Below is the data modelling image

![Shopping trend data modelling](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis-Power-BI/assets/139281995/b6946095-fad8-4ca8-a022-47b83a270e20)

###  Business Questions.
We carried out the analysis in three categories, i.e customer analysis, product analysis and regional analysis.The following were the business questions;

 1. Customer Analysis 
- How often do our customers make their purchases from us ?
- Which is payment method do most of our customers prefer ?
- What age group do most of our customers belong to?
- Which age group has the highest number of subscribers to our subscription plan and how by how many?
- What gender are most of our customers?
  
 2. Product Analysis
- Which product category do we get the most sales?
- Which are our top 10 products and how much do we make in sales from the products?
- Which payment method do most of customers use and which do we get the highest amount of money transacted in terms of sales?
- What size of product do our customers purchase the most and how much do we get in terms of sales?
- Which is the preffered shopping method?

3. Regional Analysis
- Where are most of our customers located?
- Do sales vary during different season of the year, which season do we have the highest sales?
- From our customers location which location do we get the highest sales?
- Which location do we sale the most units?

### Data Analysis
In this section we are going to look at the analysis we carried out and the insigts we get from our analysis.

## 1. Customer Analysis
#### - How often do our customers make their purchases from us ?

  ![Frequency of purchases](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis-Power-BI/assets/139281995/a8f30e89-8b4a-40a0-83c0-25b0cdc60ec6)

#### Insights

Our analysis indicates that the majority of our customers, totaling 584, prefer to shop every three months.In contrast, customers who prefer to shop on a weekly basis represent the smallest segment, totaling 539 customers. This shopping frequency represents a significant portion of our customer base and provides valuable insights into their purchasing behavior. Understanding this trend can help us tailor our marketing strategies, inventory management, and promotional efforts to better align with customer preferences and enhance their shopping experience.

#### - Which is payment method do most of our customers prefer ?

  ![Preferred payment method](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis-Power-BI/assets/139281995/7115f6dd-b8bf-413e-808e-78cb6d321ba5)

  #### Insights

Different customers prefer different payment methods, from our analysis we can be able to see the majority of our customers preferred PayPal as their payment method, with a total of 677 customers indicating this preference.
Conversely, fewer customers preferred paying through bank transfers, with 612 customers choosing this option.These insights indicate a clear preference for PayPal among our customers. Understanding these payment preferences can help us streamline our payment processes, improve customer experience and focus our efforts on enhancing the preferred payment methods.

#### - What age group do most of our customers belong to?

![Customers Age Group](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis-Power-BI/assets/139281995/2eb68d23-b8a9-4ea6-8f7c-be653712f5a1)

#### Insights
From our analysis we can be able to see that most of our customers belong to the age group 25-34 with a total of 827 customers, with the male being the dorminant customer gender with 564 male customers while the female customers were 263.
Meanwhile customers from the age group of 65+ represented the lowest segment of customers with a total of 433 total customers.

#### - Which age group has the highest number of subscribers to our subscription plan and how by how many?

![Subscription Rate](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis-Power-BI/assets/139281995/15f1915c-ae8e-413b-b26c-d322439087ff)

#### Insights
A significant portion of our customers have not subscribed to our subscription plan. Notably, the age group 25-34 has the highest number of non-subscribers, totaling to 606 customers.
On the other hand, customers from the age group 45-54 represent the highest number of subscribers, with 229 customers opting for our subscription plan.
These insights suggest that subscription uptake varies significantly across different age groups. Understanding these patterns can help us tailor our marketing strategies and subscription offers to better target the age groups with lower subscription rates, thereby enhancing overall subscription engagement and customer retention.

#### - What gender are most of our customers?

![image](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis-Power-BI/assets/139281995/4ec0b532-03d5-4e67-9aae-4295c0d26acf)

#### Insights

The majority of our customers are male, comprising 68% of the total customer base, with a count of 2,652 customers.
Female customers make up 32% of the total, with a count of 1,248 customers.
These insights indicate a significant gender disparity in our customer base, with a predominant male demographic. 

## Recommendations
- Develop marketing campaigns specifically aimed at increasing female customer engagement. Consider creating promotions, discounts, or loyalty programs that appeal to female customers. Review and potentially expand product lines to include items that may be more attractive to female customers, ensuring a broader appeal across genders.
- Design age-specific promotions and subscription offers to attract younger customers, especially those in the 25-34 age group who currently have the lowest subscription rates.Offer incentives such as exclusive content, discounts or free trials for subscriptions to encourage uptake among all age groups.
- Simplify and enhance the PayPal payment experience, given its clear preference among customers. Ensure the process is smooth and user-friendly.While focusing on PayPal, also provide clear benefits for using bank transfers and other payment methods to cater to diverse preferences and potentially reduce any barriers to use.
- Adjust inventory levels and stock replenishment cycles to align with the preference for less frequent shopping intervals. This will help in maintaining optimal stock levels and reducing excess inventory.Schedule major sales events and promotional activities around the periods when customers are most likely to shop (e.g., every three months) to maximize sales impact.




