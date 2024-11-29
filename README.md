# Amazon Sales Analysis
This is DataDNA December Product Sales Dataset Challenge!

## About
* Sales analytics is the practice of generating insights from sales data, trends, and metrics to set targets and forecast future sales performance.
* Sales analysis is mining your data to evaluate the performance of your sales team against its goals. 
* It provides insights about the top performing and underperforming products/services, the problems in selling and market opportunities, sales forecasting, and sales activities that generate revenue.

## Objective
* What was the best Year for sales? How much was earned that Year?
* What was the best month for sales? How much was earned that month?
* What City had the highest number of sales?
* What time should we display adverstisement to maximize likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

## Dataset Description   

| Column Name         | Description                                                                                          |  
|----------------------|------------------------------------------------------------------------------------------------------|  
| `Order ID`          | A unique identifier used by Amazon to track orders. Each order receives a distinct Order ID that is not duplicated. Useful for tracking shipment dates or order status. |  
| `Product`           | The product that has been sold.                                                                      |  
| `Quantity Ordered`  | The total item quantity ordered in the initial order (without any changes).                          |  
| `Price Each`        | The price of each product.                                                                           |  
| `Order Date`        | The date the customer requested the order to be shipped.                                             |  
| `Purchase Address`  | The purchase order details, including the PO number, shipping date, billing address, shipping address, requested items, quantities, and price. |  

## Insights

1. #### Total and Average Sales
* Total Sales: 34.47M, indicating a substantial volume of sales.
* Average Sales: 185.61, showing the mean sales value across different time frames.
* Maximum Sales: 3.40K, identifying the highest sales point.
* Minimum Sales: 2.99, the lowest recorded sales value.

2. #### Sales Trends by Hour
* Daily Peak: Sales peak around the middle of the day, suggesting high shopping activity during these hours.
* Daily Low: Sales start low in the early hours, gradually increase, peak in the middle of the day, and then decline towards the end of the day.

![image](https://github.com/user-attachments/assets/a04e4784-d51b-467d-acd2-df2d76832c00)

3. #### Sales Trends by Month
* Monthly Peaks: Notable spikes in sales, particularly in Months 10 (October) and 12 (December), which could be linked to seasonal shopping events like holidays and Black Friday sales.
* Monthly Lows: Lower sales in Months 8 (August) and 9 (September), indicating potential off-peak periods.

![image](https://github.com/user-attachments/assets/5ccdd0c4-8d37-4b26-abdb-396678100e46)

4. #### Monthly Sales Breakdown
* Top Month: December with 46.08M in sales, reflecting high year-end shopping activity.
* Consistent Growth: General increase in sales from the beginning of the year, peaking in December.
* Sales Fluctuations: Fluctuations in sales throughout the year, with distinct peaks and troughs corresponding to shopping trends and events.

![image](https://github.com/user-attachments/assets/b90de0ee-599c-4327-89d1-61f857d75599)

5. #### Total Sales by Top Product
* MacBook Pro Laptop: The highest-selling product with approximately 8 million sales.
* iPhone: A close second with around 7 million sales.
* ThinkPad Laptop: Third with about 5 million sales.
* Other Notable Products: Google Phone (4 million), 27in 4K Gaming Monitor (3 million), 34in Ultrawide Monitor (2.5 million), Apple Airpods Headphones (2 million), Flatscreen TV (1.5 million), Bose SoundSport Headphones (1 million), and 27in FHD Monitor (0.5 million).

![image](https://github.com/user-attachments/assets/c0696233-848f-4138-afa2-b910cb9fa3ed)

6. #### Total Sales by City
* San Francisco: The highest sales at 8,254,743.58.
* Los Angeles: Significant sales totaling 5,448,304.28.
* New York City: Substantial sales of 4,661,867.14.
* Boston: Notable sales at 3,658,627.65.
* Other cities with significant sales include Atlanta (2,794,199.07), Dallas (2,765,373.96), Portland (2,319,331.94), and Austin (1,818,044.33).
* Total Sales across Cities: 34,465,537.94, indicating widespread sales activity.

![image](https://github.com/user-attachments/assets/6aa595c7-c608-4e59-b915-eaf05f3c1653)

7. #### Product Frequency
* High Frequency Products: Apple Airpods Headphones, Google Phone, iPhone, Lightning Charging Cable, and Wired Headphones each appear 5 times in order frequency.
* Other Frequently Ordered Products: Several other products have 4 occurrences each, highlighting consistent consumer demand.

8. #### Total Sales by City (Map)
* The map visualization reinforces the sales data, with larger circles representing higher sales in cities like San Francisco, Los Angeles, and New York City.

![image](https://github.com/user-attachments/assets/c9d31e30-0bec-411b-aab9-8b8e90a0810f)

## Key Findings
1. #### What was the best Year for sales? How much was earned that Year?
* Based on the analysis, the best year for sales was 2013, with total sales peaking around 2010-2020.
* Total Earnings: While the exact earnings for 2013 are not specified, this period reflects the highest sales activity.

2. #### What was the best month for sales? How much was earned that month?
* The best month for sales was December.
* Total Earnings: December sales amounted to 46.08M, reflecting high year-end shopping activity, driven by holiday season purchases and promotional events like Black Friday and Cyber Monday.

3. #### What City had the highest number of sales?
* San Francisco had the highest number of sales.
* Total Sales: The city recorded sales of 8,254,743.58, making it a significant market for Amazon.

4. #### What time should we display advertisements to maximize the likelihood of customers buying a product?
* Optimal Advertisement Time: Advertisements should be displayed mid-day, around the peak sales hours identified in the report.
* Rationale: Sales peak around the middle of the day, indicating high shopping activity during these hours, making it the ideal time to target potential customers with advertisements.

5. #### What products are most often sold together?
* Apple AirPods Headphones frequently appear alongside iPhones and Lightning Charging Cables.
* Google Phones are commonly purchased with other tech accessories like headphones and charging cables.
* Monitors (27in 4K Gaming Monitor, 34in Ultrawide Monitor) often sold with other computer peripherals and accessories.

6. #### What product sold the most? Why do you think it sold the most?
* Top Selling Product: The MacBook Pro Laptop sold the most.
* Total Sales: Approximately 8 million units.
* Reason for High Sales: The MacBook Pro Laptop likely sold the most due to its reputation for high performance, reliability, and brand value. It's favored by professionals and students alike for its robust features, sleek design, and integration within the Apple ecosystem, making it a popular choice across various user segments
