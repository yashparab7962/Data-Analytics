
<link rel="stylesheet" type="text/css" href="style.css">


<center style="text-align:center;"><h1>Caffeine Delight Coffee Shop Sale Analysis Using POWER BI</h1></center>


![Screenshot 2024-04-30 082923](https://github.com/yashparab7962/Data-Analytics/blob/main/POWER%20BI%20/Caffeine%20Delight%20Coffee%20Shop%20Sale%20Analysis/report_images/coffe_shop_report_345634653_page-0001.jpg)

![Screenshot 2024-04-30 34958439857349](https://github.com/yashparab7962/Data-Analytics/blob/main/POWER%20BI%20/Caffeine%20Delight%20Coffee%20Shop%20Sale%20Analysis/report_images/coffe_shop_report_345634653_page-0002.jpg)



<h1><b>PROBLEM STATEMENT : </b></h1>


<p> <span style="color:red!important;font-weight:700;">Caffeine Delight Coffee </span> has been a prominent player in the coffee market for several years, offering a wide range of coffee products. Recently, the company has observed significant fluctuations in sales and is now keen to understand the underlying factors driving these changes. The management team aims to investigate various aspects, including identifying which coffee products are performing the best and the worst, analyzing seasonal sales patterns, evaluating performance across different regions, and assessing how transaction quantities, unit prices, and product categories impact overall sales. To achieve this, a comprehensive analysis is needed to pinpoint trends and patterns that could inform strategic decisions and improve sales consistency. The goal is to deliver actionable insights that will help optimize product offerings, pricing strategies, and promotional efforts.</p>

<h1><b>Objective : </b></h1>

The main objective of this project is to analyze retail sales data to gain actionable insights that will enhance the performance of the Coffee Shop



<h1><b>Dataset Description : </b></h1>

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


<h1><b>Requirements : </b></h1>
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

<h3>Sales Performance</h3>

<ul>
  <li><strong>Sales By Product Category Patterns</strong>
    <ul>
      <li><strong>Top Performers:</strong> Coffee and tea are the highest-selling categories, demonstrating their strong consumer preference and consistent demand in the market.</li>
      <li><strong>Moderate Sales:</strong> Bakery items, drinking chocolates, and coffee beans show moderate sales, indicating a steady but less pronounced consumer interest compared to coffee and tea.</li>
      <li><strong>Insight:</strong> The clear distinction in sales performance highlights coffee and tea as key revenue drivers, while the moderate performance of other categories suggests opportunities for targeted marketing or product promotions to boost their sales.</li>
    </ul>
  </li>

  <br/>
  
  <li><strong>Sales By Product Types Patterns</strong>
    <ul>
      <li><strong>Top Performers:</strong> Barista Espresso and Brewed Chai tea are the highest-selling product types, indicating strong consumer preference and high demand for these items.</li>
      <li><strong>Moderate Sales:</strong> Hot chocolate and Gourmet brewed coffee show moderate sales, suggesting consistent but less prominent consumer interest compared to Barista Espresso and Brewed Chai tea.</li>
      <li><strong>Lower Sales:</strong> Scone and Drip coffee exhibit lower sales figures, reflecting a more niche market demand or less promotional activity for these items.</li>
      <li><strong>Insight:</strong> The distinct performance of Barista Espresso and Brewed Chai tea as top sellers highlights their importance in driving revenue. The moderate and lower sales of other products suggest potential areas for targeted promotions or product enhancements to increase their market presence.</li>
    </ul>
  </li>

 <br/>

 
<li><strong>Sales By Product Size Patterns</strong>
    <ul>
         <li><strong>Large</strong> size products generate the highest sales, totaling $237,958.15, while <strong>Small</strong> size products contribute the least at $46,402.70.</li>
        <li><strong>Not Defined</strong> and <strong>Regular</strong> sizes have significant sales figures, suggesting a potential need for more precise size definitions to optimize inventory.</li>
    </ul>
  </li>

 <br/>

<li><strong>Sales By Products Patterns</strong>
    <ul>
         <li><strong>Top Products:</strong>
            <ul>
                <li><strong>Ethiopia</strong> and <strong>Sustainably Grown Organic</strong> are leading, indicating strong demand for these premium products.</li>
                <li><strong>Jamaican Coffee River</strong> and <strong>Brazilian</strong> also rank high, showing significant popularity in these varieties.</li>
            </ul>
        </li>
        <li><strong>Moderate Products:</strong>
            <ul>
                <li><strong>Columbian Medium Roast</strong> and <strong>Cappuccino</strong> have solid sales, reflecting steady customer interest.</li>
                <li><strong>Morning Sunrise Chai</strong> and <strong>Peppermint</strong> are popular, though not as dominant as top products.</li>
            </ul>
        </li>
        <li><strong>Low Products:</strong>
            <ul>
                <li><strong>Espresso Shot</strong> and <strong>Civet Cat</strong> have the lowest sales, suggesting they may need marketing adjustments or inventory review.</li>
                <li><strong>Chocolate Croissant</strong> and <strong>Scottish Cream Scone</strong> show limited demand, indicating potential opportunities for improvement.</li>
            </ul>
        </li>
    </ul>
  </li>
<br/>

<li><strong>Sales By Stores Patterns</strong>
    <ul>
         <li><strong>Hell's Kitchen</strong> leads with the highest sales, indicating strong customer preference and potentially higher traffic in this area.</li>
        <li><strong>Astoria</strong> follows closely, suggesting substantial sales and a solid customer base.</li>
        <li><strong>Lower Manhattan</strong> also shows significant sales, reflecting its importance in overall sales performance.</li>
    </ul>
  </li>
<br/>

<li><strong>Quantity vs. Unit Price Relationships</strong>
    <ul>
         <li><strong>High Volume at Low Prices:</strong> Items priced around $2.5 and $3 have the highest transaction quantities, indicating strong demand for these price points.</li>
        <li><strong>Moderate Sales at Higher Prices:</strong> Prices between $3.5 and $4.75 show significant sales, suggesting these prices are also popular but with lower transaction volumes compared to lower-priced items.</li>
        <li><strong>Low Volume at High Prices:</strong> Items priced above $10 show much lower transaction quantities, suggesting these higher prices may be less attractive to customers or less commonly purchased.</li>
    </ul>
  </li>
<br/>


<li><strong>Quantity vs. Total Sales Relationships</strong>
    <ul>
         <li><strong>Highest Sales with Low Quantities:</strong> The highest total sales of $322,430.83 and $343,529.60 are observed with quantities of 1 and 2 units, respectively. This suggests that higher total sales are associated with a lower number of transactions, possibly due to high-value items or premium products.</li>
        <li><strong>Significant Sales with Moderate Quantities:</strong> The quantity of 8 yields $3,600 in total sales, indicating a moderate total sales amount for a larger quantity of transactions.</li>
        <li><strong>Low Sales with Higher Quantities:</strong> Quantities of 3, 4, 6, and 8 show considerably lower total sales, implying that higher transaction volumes do not necessarily lead to higher total sales.</li>
    </ul>
    </ul>
  </li>
<br/>




  
</ul>



<h3>Performance Over Time</h3>
<ul>
  <li><strong>Hourly Sales Patterns</strong>
    <ul>
      <li><strong>Peak Hours:</strong> The busiest hours are from <span class="peak-hours">8 AM to 10 AM</span>, indicating a high volume of sales during these times.</li>
      <li><strong>Steady Sales:</strong> From <span class="steady-sales">10 AM to 6 PM</span>, sales remain relatively stable, fluctuating within 1 or 2 standard deviations.</li>
    </ul>
  </li>
    
<br>
    
  <li><strong>Weekly Sales Patterns</strong>
    <ul>
      <li><strong>Weekdays vs. Weekends:</strong></li>
      <li><strong>Monday to Friday:</strong> The average sales during these days are approximately <span class="high-sales">$100,000</span>.</li>
      <li><strong>Saturday and Sunday:</strong> The average sales slightly decrease to around <span class="low-sales">$97,000</span>.</li>
    </ul>
  </li>

<br>

  <li><strong>Monthly Sales Patterns</strong>
    <ul>
      <li><strong>Significant Growth:</strong> There is a notable increase in sales from March onwards, indicating a robust growth phase during the spring and early summer months.</li>
      <li><strong>Highest Sales:</strong> June records the highest sales figure, suggesting that mid-year promotions or seasonal demand could be driving this peak.</li>
    </ul>
  </li>
<br>
</ul>



<h1><b> Recommendations / Suggestions :</b> </h1>
<ul>
    <li><strong>Focus on High Performers:</strong>
        <ul>
            <li>Coffee and Tea: Continue promoting Barista Espresso and Brewed Chai tea, which are top sellers. Consider introducing new flavors or limited-time offerings to sustain interest.</li>
            <li>Premium Products: Emphasize premium products like Ethiopia and Sustainably Grown Organic coffee to leverage their strong demand.</li>
        </ul>
    </li> <br>
    <li><strong>Boost Moderate Categories:</strong>
        <ul>
            <li>Bakery Items and Hot Chocolate: Implement targeted marketing or promotional campaigns to increase visibility and attract more customers. Consider bundling these products with popular items to enhance sales.</li>
        </ul>
    </li> <br>
    <li><strong>Address Lower Sales Products:</strong>
        <ul>
            <li>Low-Selling Items: Review marketing strategies for products like Espresso Shot and Civet Cat. Consider adjusting pricing, enhancing product features, or improving promotions to boost their appeal.</li>
        </ul>
    </li> <br>
    <li><strong>Optimize Product Sizes:</strong>
        <ul>
            <li>Large Size Products: Continue promoting large size products due to their high sales volume. Evaluate if there are opportunities to offer more variety or premium options in larger sizes.</li>
            <li>Small Size Products: Assess potential to increase sales through promotional offers or bundles.</li>
        </ul>
    </li> <br>
    <li><strong>Enhance Store Performance:</strong>
        <ul>
            <li>Top Performing Stores: Leverage successful stores like Hell’s Kitchen for pilot new product launches or marketing campaigns. Analyze what drives their high sales and replicate successful strategies in other locations.</li>
            <li>Underperforming Stores: Investigate reasons behind lower performance in specific stores and address any operational or promotional gaps.</li>
        </ul>
    </li> <br>
    <li><strong>Price Strategy Adjustments:</strong>
        <ul>
            <li>High Volume at Low Prices: Maintain competitive pricing on popular items priced around $2.5 and $3. Consider promotions or discounts to drive more sales at these price points.</li>
            <li>Higher Price Items: Review pricing strategy for high-priced items above $10 to ensure they are perceived as valuable and competitive.</li>
        </ul>
    </li> <br>
    <li><strong>Manage Inventory Based on Sales Patterns:</strong>
        <ul>
            <li>Low Quantity, High Sales: Focus on stocking high-value or premium products that have higher total sales despite lower quantities.</li>
            <li>Moderate Quantities: Ensure a balanced inventory for items with moderate sales volumes to avoid stockouts or excess inventory.</li>
        </ul>
    </li> <br>
    <li><strong>Optimize Sales Timing:</strong>
        <ul>
            <li>Peak Hours: Increase staffing or promotions during peak hours (8 AM to 10 AM) to capitalize on high sales volume.</li>
            <li>Weekdays vs. Weekends: Introduce weekend-specific promotions or events to address the slight decrease in weekend sales.</li>
        </ul>
    </li> <br>
    <li><strong>Capitalize on Seasonal Trends:</strong>
        <ul>
            <li>Spring and Summer Growth: Plan and execute special promotions or product launches starting in March to capitalize on increased sales during spring and summer months.</li>
        </ul>
    </li> <br>
</ul>



<h1><b> Conclusion :</b> </h1>
<p>The analysis of the coffee shop data provides valuable insights into sales performance, customer preferences, and transaction trends. By understanding which products are most popular and when peak transactions occur, the shop can better align its inventory and staffing. Revenue analysis reveals the effectiveness of pricing strategies, while product analysis helps in assessing pricing impact. Overall, these insights can guide strategic decisions to enhance sales, optimize operations, and improve customer satisfaction.</p>
