# Dashboard Outline
Data Modeling:
7 sets of data (USA, Mexico, Japan, Germany, France, Australia) were imported and appended to form a new
master ‘Sales’ data table. Information in [Country] column in sales1 was added manually, which was
presumed to be USA based on State and Zip. [IF USA] column was added as an identifier for domestic and
oversea data. [Adjusted_Date] column was added in order to shift the dates 3 years after to current time
frame. Then ‘Date’ that contains new adjusted dates as key and fragment expansions as columns was created
and marked as date table. Data from ‘dimensions’ dataset were imported and organized into three separated
tables. Both ’bi_geo’ and ‘bi_product’ have one-to-many strong relationship that specify Geographic/Product
detail in ‘Sales’; and there is a relationship between ‘bi_Manufacturer’ and ‘bi_product’ which provides
additional manufacturer detail. Dimensional Information mentioned above can be accessed from any specific
datapoint in ‘Sales’; as for ‘Date’ table, not every calendar day links to a subtotal on ‘Sales’.
Reporting:
YTD Revenue/Units Report demonstrated revenue earned and units sold in the year of 2020. Column Chart
and Map were used to visualize the distribution of Q1 and Q2 sales. Large portion of sales volume were
generated from the No.1 and No.2 market, being the US and Australia; and by time of the year, Q2 showed a
relatively stronger performance. Two card visuals were used to display the key information. Slicers can be
applied to further narrow the results. MTD Revenue/Units Report demonstrated revenue earned and units
sold for the first 23 days of June 2020. Similar slicers on the YTD report were provided to further narrow the
results. Types of graphs and chart were changed from YTD report and Weekdays/Weekend and Days of the
Week slicers were added since a monthly report has a more day-by-day focus and means to discover
weekly/daily trends. In this case, there were significant sales drop on the past 3 Saturdays, datapoints of
most effected products (for instance, Productivity Segment) experienced zero unit sold and a surge on the
following Monday. Same YTD time slot was chosen for the 2019/2020 Comparison tab. Card with percentage
revenue change within any selected time slot gives the most straight-forward comparison. Q2 showed a
relatively stronger performance on both years. Sales on days of the week were visualized and compared in
percentage distribution in total sales revenue; also, monthly sales percentages were visualized. Interestingly,
unique geographic location of Australia (only Southern Hemisphere market), with reverse seasons, gave a
stronger Q1 but were overruled by its own 2020 data. Last but not least, 2019/2020 Product Detail broke
down revenue even more by product segments, categories, and geography. The most recent 18 months were
chosen to have its time relevancy aligned with the previous tabs. Cards were used to demonstrate global
market shares and product counts within adjustable time slot. Top products show market dominance not
only in terms of Segment and Categories, but also down to specific Products. The column chart with the Top
10 products that generated the most revenue consist over 25% of total revenue in select time slot. 9 out of
10 belongs to the most popular Category and 10 out of 10 belongs to the most popular segment.
*If a company account of Power BI which allows the download of more features and visualization (such as
Chiclet Slicer and Text Filter) is given, even more interesting and interactive dashboard analysis can be
implemented to the report.
