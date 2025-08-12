# Business-Insights-360-Power-BI-Dashboard

This dashboard, "Business Insights 360," provides a multifaceted view of a company's performance across various key business functions: **Finance**, **Sales**, **Marketing**, and **Supply Chain**. The project utilizes Power BI to visualize data and extract actionable insights, enabling stakeholders to make data-driven decisions.

📊 **Dashboard Overview**

The dashboard is structured with a clear navigation pane on the left, allowing users to switch between different business views. The main canvas displays a variety of visuals, including tables, charts, and key performance indicators (KPIs). The dashboard effectively uses filters and slicers to allow for granular analysis by time period, region, and product segment.

📈 **Analysis & Interpretation**

**Finance View**

The Finance View focuses on the company's profitability.

**Key Metrics**: It displays key financial metrics like **Net Sales**, **Gross Margin (GM) %**, and **Net Profit %**.

**Insights**: The dashboard shows a total **Net Sales of $3.74 billion** and a **Gross Margin of 38.08%**. The line chart "Net Sales Performance Over Time" reveals a fluctuating but generally upward trend in sales, with a noticeable dip around the beginning of the year. The table at the bottom right, "Top / Bottom Products & Customers by Net Sales," highlights the best-performing product categories like Notebooks and Desktop, while also showing a significant performance change in the NA (North America) region.

**Sales View**

The Sales View provides a detailed breakdown of sales performance by product, region, and customer.

**Key Metrics**: The main metrics are **NS (Net Sales)**, **GM (Gross Margin)**, and **GM%**.

**Insights**: The "Product Performance" table reveals that **Notebooks** and **Desktop** are the top-selling segments, contributing significantly to both sales and gross margin. The "Region / Market / Customer Performance" table highlights that the **NA region** is a major contributor to sales, while other regions like EU and APAC also perform well. The "Performance Matrix" visualizes this by showing a high concentration of sales in certain regions and divisions. The "Unit Economics" section breaks down gross margin and cost of goods sold (COGS) to show the profitability of each unit sold.

**Marketing View**

The Marketing View focuses on market share and customer/product insights.

**Key Metrics**: This view tracks **Revenue**, **Revenue by Division**, and **Revenue by Channel**.

**Insights**: The donut charts show a significant portion of revenue coming from the **PC division** and the **Direct Distributor channel**. The line chart "Yearly Trend by Revenue, GM%, Net Profit%, PC Market Share %" provides a historical view, showing that while revenue and gross margin are relatively stable, market share has fluctuated. The "Top 5 Customers by Revenue" and "Top 5 Products by Revenue" tables provide a clear view of the most valuable customers and products, highlighting key areas for marketing focus.

**Supply Chain View**

The Supply Chain View analyzes forecast accuracy and potential risks.

**Key Metrics**: The main metrics are **Forecast Accuracy**, **Net Error**, and **Absolute Error**.

**Insights**: The overall forecast accuracy is **81.17%**, which is a solid performance but leaves room for improvement. The line chart "Accuracy / Net Error Trend" shows the forecast accuracy over time, indicating periods where forecasting was more challenging. The tables "Key Metrics by Customer" and "Key Metrics by Segment" identify specific customers (Amazon, Atlas Stores) and product segments (Networking, Notebook) where forecast accuracy is low. The Risk column often indicates "OOS" (Out of Stock), a critical business problem that needs to be addressed.

🛠️ **Methods Used**

The dashboard appears to be built using a combination of Power BI's standard features:

**DAX (Data Analysis Expressions)**: It's highly likely that DAX formulas were used to create the various calculated measures like Gross Margin (GM), Net Profit %, and Forecast Accuracy.

**Power Query**: Data transformation and cleaning were likely performed using Power Query to prepare the raw data for analysis.

**Visualizations**: The dashboard utilizes a variety of built-in Power BI visuals, including:

**Card visuals** for displaying key KPIs.

**Tables** and **Matrices** for detailed breakdowns.

**Line charts** for trend analysis.

**Donut charts** and **Bar charts** for proportional and categorical comparisons.

**Scatter plots** or similar visuals for performance matrix representations.

💡 **Suggestions & Improvement Areas**

**Forecast Accuracy**: The Supply Chain View identifies several customers and segments with low forecast accuracy and Out of Stock (OOS) risks. The company should investigate these specific instances to understand the root causes, which could be anything from unreliable demand data to supply chain disruptions.

**Product Performance**: While Notebooks and Desktop are strong performers, the company should analyze the underperforming segments (Storage, Networking) to either improve their profitability or reallocate resources to more successful products.

**Customer Focus**: The "Top 5 Customers by Revenue" section is an excellent starting point. The company should leverage this information to build stronger relationships, potentially offering loyalty programs or targeted promotions to these high-value customers.

**Operational Efficiency**: The "Unit Economics" section can be expanded to include more detailed cost components beyond COGS, such as shipping costs, labor, and overhead, to get a more granular view of profitability.

**Data Granularity**: The dashboard provides a good high-level overview. Adding more detailed drill-down capabilities, perhaps into specific product models or individual transactions, would offer deeper insights.

📝 **Conclusion**

This Power BI dashboard is a powerful tool for a holistic view of the business. It successfully consolidates complex data into an easy-to-understand format, allowing users to quickly identify key trends, performance gaps, and areas of opportunity. By leveraging these insights, the company can make more informed decisions to enhance profitability, optimize operations, and drive future growth. The identified areas for improvement, particularly in supply chain accuracy and underperforming segments, provide clear actionable steps for the business to pursue.

**Live Dashboard**: https://app.powerbi.com/view?r=eyJrIjoiNWJkMzA1OTktZTY0NC00MWFmLTg1YTItZmJkYmU0YWYxODMzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

Dashboard
