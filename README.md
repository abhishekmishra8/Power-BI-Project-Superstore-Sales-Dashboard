[Follow me on LinkedIn](https://www.linkedin.com/in/abhishekmishra3/) &nbsp;&nbsp; | &nbsp;&nbsp; [Github Repository Link](https://github.com/abhishekmishra8/Power-BI-Project-Superstore-Sales-Dashboard) &nbsp;&nbsp; | &nbsp;&nbsp; [Github Page Link](https://abhishekmishra8.github.io/Power-BI-Project-Superstore-Sales-Dashboard/)

# See More Projects

<details open>
<summary>Dashboards List</summary>
<br>
- [Bank Domain Dashboard](https://abhishekmishra8.github.io/Power-BI-Project-Bank-Domain/)
- [HR Employees Dashboard](https://abhishekmishra8.github.io/PowerBI_Project_HR_Employees/)
</details>


Project Report Video shown below:
<video width="650" height="360" controls autoplay muted loop>
<source src="Files/Images/Dashboard Video.mp4" type="video/mp4">
click the Github Page Link to see the video
</video>

<br><br>
Project Report and Dashboard Sreenshot shown below:  
<img src="Files/Images/Sales Dashboard Superstore.JPG" width="400" height="250" /> &nbsp;&nbsp; <img src="Files/Images/Dashboard Forecast.JPG" width="400" height="250" />

**Objective** : To contribute to the success of a business by utilizing techniques, specifically focusing on time series analysis, to provide valuable insights and accurate sales forecasting.
- Dashboard Creation
- Data Analysis
- Sales Forecasting
- Actionable Insights and Recommendations

**Business Insights Report: Analyzing Key Findings**

*Executive Summary:*
This report presents a comprehensive analysis of key findings derived from our business data. By examining payment modes, regions, customer segments, sales performance, profitability, shipping modes, product categories, sales forecast, and state-wise sales, we have gained valuable insights that can guide our business decisions and strategies. These findings shed light on customer preferences, market dynamics, and areas of opportunity. By leveraging these insights, we can optimize our operations, drive sales growth, and enhance profitability.

*Payment Mode Analysis:*
Cash on Delivery (COD) emerged as the most popular payment mode, accounting for 42.62% of the total sum of sales. This finding suggests that a significant portion of our customer base prefers the convenience and trust associated with paying upon delivery. We should ensure a seamless COD process while exploring incentives to encourage customers to adopt online or card-based payments, which can streamline operations and reduce cash-handling risks.

*Regional Analysis:*
The West region stood out with the highest sum of sales, accounting for 33.37% of the total. This dominance presents an opportunity to allocate additional resources for marketing and promotional activities tailored to this region. By understanding customer preferences and establishing strong local partnerships, we can enhance brand visibility and engage effectively with the West region's market.

*Segment Analysis:*
The Consumer segment was the top contributor to sales, accounting for 48.09% of the total sum. To capitalize on this segment's potential, we should implement personalized marketing campaigns, loyalty programs, and customer retention initiatives. Understanding consumer preferences and delivering exceptional customer service will be key to strengthening our position in this segment.

*Sales Analysis:*
Sales in 2020 surpassed those in 2019, indicating positive growth. December was a critical month, contributing 10.61% of the total sum of sales in 2020. We should leverage the holiday season by designing targeted marketing campaigns, offering exclusive promotions, and optimizing inventory management. Providing excellent customer service during this peak period will enhance customer satisfaction and drive repeat business.

*Profit Analysis:*
Profitability in 2020 outperformed 2019, with December 2019 and March 2020 being notable months. By analyzing these divergences, we can identify the underlying factors and develop strategies to optimize profitability. Factors such as seasonality, market conditions, costs, pricing, and customer behavior should be carefully evaluated to mitigate risks and improve profitability throughout the year.

*Shipping Mode Analysis:*
Standard Class emerged as the most preferred shipping mode, accounting for 58.27% of the total sum of sales. Understanding customer preferences for different shipping modes will help optimize logistics and improve customer satisfaction. Balancing efficiency and cost-effectiveness while meeting customer expectations should be a priority across all shipping modes.

*Product Category Analysis:*
Office Supplies led in sales, followed by Technology and Furniture. Office Supplies accounted for 41.11% of the total sum of sales, highlighting its popularity. By understanding the demand and preferences for each category, we can optimize product offerings, pricing strategies, and marketing campaigns to maximize sales and profitability.

*Sales Forecast Analysis:*
Sales exhibited a significant upward trend, with a 3,924.22% increase between January 1, 2019, and December 31, 2020. Recognizing this trend and understanding the factors driving it, such as promotions or market demand, will allow us to allocate resources effectively and capitalize on future growth opportunities.

*State-wise Sales Analysis:*
California dominated sales, with the highest sum, accounting for 30.92% of the total. Analyzing sales performance across states helps us identify potential growth areas, target marketing efforts, and tailor strategies to local market conditions.

*Conclusion:*
The findings presented in this report provide valuable insights into various aspects of our business. By analyzing payment modes, regions, customer segments, sales performance, profitability, shipping modes, product categories, sales forecasts, and state-wise sales, we can make informed decisions and formulate strategies to optimize operations, drive growth, and enhance profitability. It is crucial to continue monitoring these metrics, conduct further analysis, and adapt our strategies based on evolving customer preferences and market dynamics. By leveraging these insights effectively, we can stay ahead of the competition and deliver exceptional value to our customers.




### Key Learnings from the Power BI Project on Superstore Sales Dashboard:-

1. Data Import: Importing CSV files into Power BI and connecting them to create a dataset for analysis.

2. Data Transformation: Using Power Query to clean and prepare the data. This involves removing unnecessary columns and ensuring proper data types for accurate analysis.

3. Visual Customization: Changing the canvas background to enhance the overall look and feel of the dashboard.

4. Clustered Bar Chart: Creating clustered bar charts to visualize sales by category, subcategory, and ship mode. This allows for easy comparison and identification of trends.  
<img src="Files/Images/Filter of Top 3 Sales by Sub Category Bar Chart.JPG" width="350" height="450" />

5. Stacked Area Chart: to compare sales and profit year over year. Analyzing monthly sales and profit trends provides insights into performance patterns.  
<img src="Files/Images/Area Chart Sales Profit Insight YoY.JPG" width="600" height="350" />

6. Map Visualization: Displaying state-wise sales and profit using a map.
- To Enable value on Map follow the steps. File -> Options & Settings -> Options -> Security -> tick 'Use Map and Filled Map Visuals'.  
<img src="Files/Images/Map Value Enable Setting.JPG" width="400" height="400" />

7. Donut Chart: to showcase sales by segment, payment mode, and region.

8. Slicer: to filer the report by region.

9. Display the KPIs using Card.
- Sum of Sales, Profit, Quantity, Average Delivery Time ( Create New column Step 9)

10. Add new Column. This helps analyze the efficiency of order processing and delivery.
- AvgDeliveryTime = DATEDIFF('SuperStore_Sales_Dataset'[Order Date],'SuperStore_Sales_Dataset'[Ship Date],DAY)

11. Sales Forecast: Adding a new page to showcase sales forecast using a line chart visual. This allows users to analyze and predict future sales trends based on historical data.

Through these key steps, the Superstore Sales Dashboard in Power BI enables users to gain valuable insights, identify trends, and make data-driven decisions to optimize sales performance and improve overall business outcomes.
