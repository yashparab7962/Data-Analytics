
<link rel="stylesheet" type="text/css" href="style.css">


<center style="text-align:center;"><h1>Caffeine Delight Coffee Shop Sale Analysis Using POWER BI</h1></center>


![Screenshot 2024-04-30 082923](https://github.com/yashparab7962/Data-Analytics/blob/main/POWER%20BI%20/Caffeine%20Delight%20Coffee%20Shop%20Sale%20Analysis/report_page-0001.jpg)


<b><h2>PROBLEM STATEMENT</h2></b>

<p> <span style="color:red!important;font-weight:700;">Caffeine Delight Coffee </span> has been a prominent player in the coffee market for several years, offering a wide range of coffee products. Recently, the company has observed significant fluctuations in sales and is now keen to understand the underlying factors driving these changes. The management team aims to investigate various aspects, including identifying which coffee products are performing the best and the worst, analyzing seasonal sales patterns, evaluating performance across different regions, and assessing how transaction quantities, unit prices, and product categories impact overall sales. To achieve this, a comprehensive analysis is needed to pinpoint trends and patterns that could inform strategic decisions and improve sales consistency. The goal is to deliver actionable insights that will help optimize product offerings, pricing strategies, and promotional efforts.</p>

<b><h2>Objective</h2></b>
The main objective of this project is to analyze retail sales data to gain actionable insights that will enhance the performance of the Coffee Shop


<h2>Dataset Description</h2>
<ul>
    <li><b>transaction_id:</b> Unique identifier for each transaction. <br> <i>Sample Data:</i> T001, T002</li>
    <li><b>transaction_date:</b> Date on which the transaction occurred. <br> <i>Sample Data:</i> 2024-07-01, 2024-07-02</li>
    <li><b>transaction_time:</b> Time at which the transaction took place. <br> <i>Sample Data:</i> 09:30:00, 14:45:00</li>
    <li><b>transaction_qty:</b> Quantity of items purchased in the transaction. <br> <i>Sample Data:</i> 2, 5</li>
    <li><b>store_id:</b> Unique identifier for the store where the transaction occurred. <br> <i>Sample Data:</i> S01, S02</li>
    <li><b>store_location:</b> Physical location of the store. <br> <i>Sample Data:</i> Downtown, Uptown</li>
    <li><b>product_id:</b> Unique identifier for each product. <br> <i>Sample Data:</i> P001, P002</li>
    <li><b>unit_price:</b> Price per unit of the product. <br> <i>Sample Data:</i> $3.50, $4.00</li>
    <li><b>product_category:</b> Category to which the product belongs. <br> <i>Sample Data:</i> Coffee, Pastry</li>
    <li><b>product_type:</b> Type or variant of the product. <br> <i>Sample Data:</i> Latte, Croissant</li>
    <li><b>product_detail:</b> Additional details about the product. <br> <i>Sample Data:</i> Medium size, Almond flavored</li>
</ul>

<p><b>Note:</b> Follow the mockup diagram provided by the client for designing the final report. Ensure that the structure, layout, and visual elements align with the mockup to maintain consistency with the client's expectations.</p>


<h2>Recommended Insights</h2>
<ul>
    <li><b>How do sales vary by day of the week and hour of the day?</b> Analyze sales patterns to determine how they fluctuate throughout the week and day.</li>
    <li><b>Are there any peak times for sales activity?</b> Identify specific times when sales activity is highest to optimize store operations.</li>
    <li><b>What is the total sales revenue for each month?</b> Calculate and compare total monthly revenue to track financial performance over time.</li>
    <li><b>How do sales vary across different store locations?</b> Evaluate sales performance at each store location to identify high and low-performing areas.</li>
    <li><b>What is the average price/order per person?</b> Determine the average expenditure per order to gauge customer spending behavior.</li>
    <li><b>Which products are the best-selling in terms of quantity and revenue?</b> Identify top-performing products based on sales volume and revenue generated.</li>
    <li><b>How do sales vary by product category and type?</b> Analyze sales data across different product categories and types to understand preferences and trends.</li>
</ul>





<h2>Tools and Technology</h2>
<ul>
    <li><b>Microsoft POWER BI:</b> Comprehensive tool for data import, cleaning, exploration, advanced analysis, and visualization. Allows for the creation of interactive dashboards and reports.</li>
    <li><b>Power Query:</b> Integrated with Power BI for advanced data transformation and cleaning.</li>
    <li><b>Data Visualization:</b> Utilizes Power BI’s extensive library of charts, graphs, and maps to create visual representations of data.</li>
    <li><b>Statistical Analysis:</b> Leverages Power BI’s DAX functions and integration with R and Python for complex statistical analysis.</li>
    <li><b>Reporting:</b> Facilitates the generation of dynamic summary reports and dashboards that can be shared and collaborated on within Power BI Service.</li>
</ul>





<h2>Steps for Coffee Shop Data Analysis</h2>
<ol>
    <li><b>Imported Data:</b> Loaded the coffee shop dataset into Excel.</li>
    <li><b>Cleaned Data:</b> Addressed duplicates, missing values, and ensured correct data types.</li>
    <li><b>Explored Data:</b> Conducted basic descriptive statistics and visual inspections.</li>
    <li><b>Analyzed Trends:</b> Evaluated patterns and trends in transactions, sales, and products.</li>
    <li><b>Visualized Insights:</b> Created charts and graphs to visualize key findings.</li>
    <li><b>Summarized Findings:</b> Compiled insights into a summary report or dashboard.</li>
</ol>

<h2>Insights</h2>
<ul>
  <li><strong>Hourly Sales Patterns</strong>
    <ul>
      <li><strong>Peak Hours:</strong> The busiest hours are from <span class="peak-hours">8 AM to 10 AM</span>, indicating a high volume of sales during these times.</li>
      <li><strong>Steady Sales:</strong> From <span class="steady-sales">10 AM to 6 PM</span>, sales remain relatively stable, fluctuating within 1 or 2 standard deviations.</li>
    </ul>
  </li>
  <li><strong>Weekly Sales Patterns</strong>
    <ul>
      <li><strong>Weekdays vs. Weekends:</strong></li>
      <li><strong>Monday to Friday:</strong> The average sales during these days are approximately <span class="high-sales">$100,000</span>.</li>
      <li><strong>Saturday and Sunday:</strong> The average sales slightly decrease to around <span class="low-sales">$97,000</span>.</li>
    </ul>
  </li>

  <li><strong>Monthly Sales Patterns</strong>
    <ul>
      <li><strong>Significant Growth:</strong> There is a notable increase in sales from March onwards, indicating a robust growth phase during the spring and early summer months.</li>
      <li><strong>Highest Sales:</strong> June records the highest sales figure, suggesting that mid-year promotions or seasonal demand could be driving this peak.</li>
    </ul>
  </li>

</ul>


<ol>
    <li><b>Sales Performance:</b> Identify which products or categories generate the most revenue and which are underperforming.</li>
    <li><b>Customer Preferences:</b> Understand popular products, peak transaction times, and preferred store locations.</li>
    <li><b>Transaction Trends:</b> Analyze transaction volumes by time of day, day of the week, and seasonality to optimize staffing and inventory.</li>
    <li><b>Revenue Analysis:</b> Evaluate the impact of different pricing strategies and promotions on overall sales.</li>
    <li><b>Product Analysis:</b> Determine the relationship between unit price and quantity sold to assess pricing effectiveness.</li>
</ol>


<h2>Conclusion</h2>
<p>The analysis of the coffee shop data provides valuable insights into sales performance, customer preferences, and transaction trends. By understanding which products are most popular and when peak transactions occur, the shop can better align its inventory and staffing. Revenue analysis reveals the effectiveness of pricing strategies, while product analysis helps in assessing pricing impact. Overall, these insights can guide strategic decisions to enhance sales, optimize operations, and improve customer satisfaction.</p>
