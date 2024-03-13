# Ecommerce-Dataset
EDA and Cohort Analysis in SQL

*Overview*: TheLook is an e-commerce website specializing in clothing. The dataset contains information about customers, products, orders, logistics, web events, and digital marketing campaigns.


https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce?q=search&referrer=search&project=sincere-torch-350709


- **Orders table**: Records all orders placed by customers.
- **Order_items table**: Records the list of items purchased in each order ID.
- **Products table**: Records details of products sold on The Look, including price, brand, and product categories.


**MAIN CONCLUSION**

**EDA**
![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/c57d85db-a9b5-4501-b5ac-022d26181ad3)

The data indicates consistent growth in both user count and order volume over time, with occasional fluctuations. There is a seasonal trend observed around the end of the year (November and December), where user counts and order volumes consistently peak compared to other months.

![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/d60e4dfa-6475-4311-ba97-9c5bb1587003)

The data shows a generally increasing trend in distinct users over time, with occasional fluctuations. However, average order value has remained relatively stable from $52 to $63.

![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/c4d9953c-d59c-4f7c-9cd3-c88160cb309f)    ![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/359b8759-bb79-4e40-9228-eaa04e5898c2)

I want to find insights about the customer segmentation. The youngest customer in both gender groups is 12 years old, while the oldest customer is 70 years old. And there is a higher representation of males in the oldest age group.

![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/8220977b-b8ed-4078-939a-8800d9bf7d70)

This dynamic chart allows you to visualize the total revenue by day for each product category over the past three months (assuming the current date is April 15, 2022). You can filter by product categories and dates to examine revenue trends for specific items.

![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/bdce6dc8-c738-4e4d-af32-76f774c95ee2)

I want to see the top 5 products with the highest profits for each month. You can use the slicer to choose a specific month-year. This feature offers both an overview and detailed performance for the chosen time period, supporting further analysis.

**Retention Cohort**

![image](https://github.com/QuynhNhu0810/Ecommerce-Dataset/assets/144129608/ee0a1871-29d3-4475-8f28-a0dd00ce498a)

For each cohort, I only track the first 3 months (indexed from 1 to 4). 
The cohorts from 2019 to the first half of 2022 had a very low retention rate over the years, ranging from 1 to 4%. However, this rate improved in the group from the second half of 2022 to 2023, increasing to 5-18%.

*Proposed actions:*

- Focus on developing customer care activities and implement initiatives to increase interaction and retain customers.
- Conduct surveys and gather feedback to understand why some cohorts have low retention rates.
- Develop marketing campaigns and promotions to attract customers with low retention rates.
- Consider loyalty programs or special offers to retain customers in new cohorts.
