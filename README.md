# Shopping-Trends-Analysis


### Project Overview

In today's competitive retail landscape, understanding shopping trends is crucial for business to stay ahead. This report  delves into a comprehensive analysis of shopping trends, examining various aspects such as customer behaviour, product preferences and regional differences. Our goal i to provide actionable insights that can help business optimize their strategy and enhance customer satisfaction.

### Data Sources
The dataset was sourced from [kaggle](https://www.kaggle.com/datasets/riturajpradhan/shopping-trends).This dataset 'Shopping Trends Data  contains detailed shopping trends , it includes vital information on customer demographics, purchasing behaviour and product specifics enable a comprehensive analysis of shopping trends.

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

### Data Modelling
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
- Which is the preffered shipping method?

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


#### Dashboard
![Customer Analysis Dashboard](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/9db2a039-d229-40cd-affe-cdac1134936f)



## 2. Product Analysis
In this section we are going to look at the different perfomance of our products in terms of sales and units sold.
#### - Which product category do we get the most sales?

![Total Sales](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/0c623246-05f3-48b6-be87-258545b38833)

#### Insights
The clothing product category generates the highest sales, with a total sales amount of $2,646,306. This indicates a strong customer preference for clothing items, making it the most lucrative product category.The accessories category follows, with total sales amounting to $1,896,187. This shows a significant demand for accessory products, contributing substantially to overall sales.This category generates the lowest sales, with a total sales amount of $462,084. This suggests a lower customer interest in outerwear products compared to other categories.These insights highlight the dominant role of clothing products in driving our sales revenue, with accessories also playing a significant part.

#### - Which are our top 10 products and how much do we make in sales from the products?

![Top 10 products](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/400958ca-59b5-47bc-823f-42386792e2ca)

#### Insights
Jewelry tops the sales chart with a total sales amount of $292,230, indicating a high demand and strong customer preference for jewelry items.Among the top 10 products, boots have the lowest sales, with a total amount of $237,137. Although it is the lowest in this segment, it still represents a significant contribution to overall sales.The sales amounts for the top 10 products show a relatively close distribution, indicating a well-diversified portfolio where multiple products contribute significantly to total sales.

#### - Which payment method do most of customers use and which do we get the highest amount of money transacted in terms of sales ?

![Payment Method](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/1ba43ea3-7cf4-40ed-98b0-d744c5bcd387)

#### Insights
Venmo is the most preferred payment method among our customers, with a total payment amount of $1,047,488. This indicates a strong customer preference for the convenience and ease of use associated with Venmo.Debit cards are the least preferred payment method, with a total payment amount of $941,928. While still significant, this amount is lower compared to other payment options.These insights highlight a clear preference for Venmo among our customers, suggesting its perceived convenience and user-friendly features. 

#### - What size of product do our customers purchase the most and how much do we get in terms of sales ?
Medium-sized products are the most preferred by our customers, with total sales amounting to $2,668,362. This indicates a strong customer preference for medium-sized items, making them the highest-selling product size category.Extra large products have the lowest sales, with a total amount of $665,470. This suggests a lower customer demand for extra large sizes compared to other product sizes.These insights highlight the significant preference for medium-sized products among our customers. 

#### - Which is the preffered shipping method ?

![Preffered shipping method](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/a792feec-2db2-4502-9b4f-013bc5f680d1)

#### Insights

Free shipping is the most preferred shipping method among our customers, with a total of 675 customers opting for this option. This indicates a strong preference for cost-saving shipping options.2-day shipping has the lowest number of customers preferring this method, with 627 customers choosing this option. Although it is the least preferred, it still has a significant customer base.These insights highlight a clear preference for free shipping, reflecting the importance of cost considerations for our customers. 

## Recommendations
- Given the strong preference for free shipping, consider offering free shipping promotions more frequently or setting a minimum purchase threshold for free shipping to encourage higher order values.To increase the uptake of 2-day shipping, emphasize its benefits such as quick delivery times, and offer occasional discounts or incentives for selecting faster shipping options.
- Ensure adequate stock levels for medium-sized products to meet the high demand. Regularly monitor sales trends to avoid stockouts. Create targeted marketing campaigns to promote extra large products, potentially highlighting their unique benefits or running special promotions to boost their sales.
- Given the preference for Venmo, ensure the payment process is seamless and promoted during checkout. Highlight any additional security or convenience features to encourage its continued use.Offer incentives such as discounts or cashback for using less preferred payment methods like debit cards to balance payment utilization and provide more options for customers.
- Leverage the high demand for jewelry by highlighting it in marketing campaigns, offering exclusive deals, and ensuring a diverse and appealing inventory.Create targeted promotions for boots, such as seasonal discounts or bundled offers, to enhance their appeal and drive sales.
- Continue to focus on clothing and accessories as key revenue drivers. Ensure these categories are well-stocked and promoted through various marketing channels.Investigate potential reasons for the lower sales of outerwear and consider redesigning, rebranding, or offering special promotions to stimulate interest and sales in this category.

## Dashboard

![Product Analysis](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/627c67c8-cbee-43f3-9b57-2108f868411d)

## 3. Regional Analysis
Regional analysis is a critical approach in understanding the geographic distribution of business activities, customer behaviors, and market trends. 

#### - Where are most of our customers located?

![Customer distribution](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/bc1295a0-89a3-435b-be82-b3b7a5f99f52)

#### Insights
 Montana has the highest number of customers, with a total of 96 customers. This indicates a strong presence and potentially higher market penetration in this region.Both Delaware and Maryland have the lowest number of customers, with 86 customers each. This suggests a lower market presence in these regions.These insights highlight the significant customer base in Montana and the relatively lower customer engagement in Delaware and Maryland.

 #### - Do sales vary during different season of the year, which season do we have the highest sales?
 
 ![Seasonal Sales](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/5d7f82e2-12f2-484c-95cb-6e60c25d2e11)

 #### Insights
The winter season generates the highest sales, with a total amount of $1,517,469, accounting for 25.63% of the total sales. This indicates a strong customer purchasing activity during the winter months, making it the most lucrative season for our business.The summer season has the lowest sales, with a total amount of $1,429,054, representing 24.14% of the total sales. Although it is the lowest, it still constitutes a significant portion of the overall sales.These insights highlight the peak sales period during the winter season, suggesting that customers are more inclined to make purchases during this time.

#### - From our customers location which location do we get the highest sales?

![Total Sales by Location](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/7cfc5bd1-4d87-41b1-a579-9f694fbe00ca)


#### Insights
Illinois is the leading location in terms of sales, generating a total of $150,662. This indicates a strong market presence and high customer engagement in this state.California has the lowest sales among the top 10 locations, with a total of $133,017. While still significant, this amount is lower compared to other top-performing locations.These insights highlight the robust sales performance in Illinois, suggesting it as a key market for our business. The relatively lower sales in California, despite being a top 10 location, indicate potential for growth and improvement

#### - Which location do we sale the least units?

![Bottom 10 locations by sales](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/d9a50eaa-5742-4056-a5db-e13a42263df5)

#### Insights 
Florida is the leading location among the bottom 10, with a total of 1,777 units sold. This indicates that, despite being in the lower tier, Florida still maintains a relatively higher sales volume compared to the other locations in this segment.Kansas has the lowest number of units sold among the bottom 10 locations, with a total of 1,473 units sold. This suggests a lower customer engagement and sales performance in this state.These insights highlight the need to address the sales performance in these bottom 10 locations. Despite Florida leading in this segment, there is still room for improvement. 

## Recommendations
- Develop specific marketing campaigns aimed at increasing visibility and engagement in the bottom 10 locations. Highlight unique offers and promotions to attract more customers.Implement localized promotions and discounts tailored to the preferences and needs of customers in these regions, with a special focus on Kansas to boost sales where it is lowest.Gather and analyze customer feedback from these locations to understand any specific barriers or challenges they face. Use this information to make necessary adjustments to products or services.
- Capitalize on the high sales during the winter season by ramping up inventory, launching winter-specific products, and increasing promotional activities.Develop strategies to boost summer sales, such as introducing summer-exclusive products, running summer sales events, and creating targeted marketing campaigns to drive customer interest during the summer months.
- Continue to reinforce and leverage the strong customer base in Montana by maintaining high inventory levels, offering loyalty programs, and enhancing customer service.Implement targeted customer acquisition campaigns in Delaware and Maryland, such as personalized marketing efforts, regional partnerships, and community engagement activities to increase brand visibility and attract new customers.
- Maintain and further enhance the sales performance in Illinois by offering exclusive deals, improving customer service, and ensuring the availability of popular products.Increase efforts to boost sales in California by understanding local market preferences, optimizing product offerings, and running targeted promotional campaigns to attract more customers.


## Dashboard

![Regional Analysis](https://github.com/ezraonyinkwa/Shopping-Trends-Analysis/assets/139281995/d7b62f85-8444-480a-a32a-01fb531cc4e0)








  







