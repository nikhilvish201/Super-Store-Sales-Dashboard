# Super-Store-Sales-Dashboard
This Power BI dashboard provides a comprehensive analysis of Super Store sales performance across multiple business dimensions. It tracks key metrics such as Total Sales, Quantity Sold, Profit, and Average Delivery Time, while enabling deeper insights across segments, categories, regions, time periods, and shipping/payment behaviors.
Key Features

KPIs Overview:
Displays core performance metrics including total sales (522.4K), total quantity (7298), profit (67.9K), and average delivery time.

Segment Analysis:
Breaks down sales across Consumer, Corporate, and Home Office segments to identify customer groups driving the highest revenue.

Time Series Trends (YoY):
Monthly sales and profit comparisons for 2019 vs. 2020, highlighting growth patterns, seasonal variations, and performance dips.

Regional Performance:
An interactive map visual that shows the geographical distribution of sales and profit, highlighting top-performing and underperforming states.

Category & Sub-Category Insights:
Visuals showing sales distribution across categories like Office Supplies, Technology, and Furniture, and sub-categories like Phones, Chairs, and Binders.

Payment Mode Breakdown:
Distribution of transactions across COD, Cards, and Online payment modes.

Shipping Mode Analysis:
Sales split by Standard, Second Class, First Class, and Same Day shipping options to understand delivery preferences and cost implications.

Region Filter:
A slicer enabling quick comparison between Central, East, South, and West regions.

💡 Insights Generated

Consumer segment contributes the highest sales share.

Office Supplies leads in category sales.

West region drives majority of total revenue.

Standard shipping is the most preferred shipping mode.

Sales and profit show an upward YoY trend with occasional monthly volatility.

5-Day Sales Forecast – Key Insights
1. Sales show extreme day-to-day volatility — forecasting is harder than normal.
Your historical line (top chart) is highly noisy, meaning the business doesn’t follow a smooth pattern.
This usually happens because of:
inconsistent order volumes
promotional spikes
seasonality mixed with random activity
returns and cancellations

Impact:
The model’s confidence interval becomes wider — which you can clearly see in the shaded forecast area.

**2. The forecast suggests a moderate short-term increase in sales.
In the bottom chart, the yellow forecast line for the upcoming 15 days trends slightly upward, not downward.
So the model expects:
sales to rise
but not dramatically
and with a wide uncertainty band
This is realistic for a store with high noise and no clear seasonality.

3. The confidence interval is large — meaning your future demand is unpredictable.
The shaded prediction band is very wide, which signals the model is saying:
“Sales will increase, but I can’t predict the exact number with high certainty.”
This happens when historical data has:
too many spikes
irregular seasonality
missing patterns

Action:
You need to break forecasting down by:
product category
region
or weekly aggregation
This will reduce noise and increase accuracy.

4. California dominates total sales and will heavily influence your forecast accuracy.
The “Sum of Sales by State” bar chart shows:
California massively outweighs other states
New York is a distant second
Most other states barely contribute
If California has volatile behavior, your total sales prediction will also be volatile.

Action:
Forecast separately for top states instead of aggregating everything.

5. Your model is picking up a post–holiday dip followed by a recovery.
End of December → early January shows a drop (historical trend).
The forecast expects a stabilized recovery, which aligns with typical retail behavior after holidays.
This is why the first few forecast points are lower, then rise gradually.

📁 Tools & Techniques Used

Power BI (Data Modeling, DAX, Visualization Design)

Data Cleaning & Transformation in Power Query

Custom visuals: Donut charts, line charts, bar charts, map visuals

Slicers for regional filtering and YoY comparison
