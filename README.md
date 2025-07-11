# Blinkit Sales Analysis <br>
This repository contains a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution. The <br>analysis identifies key insights and opportunities for optimization using various Key Performance Indicators (KPIs) and visualizations<br> in Python.<br>

##Table of Contents<br>
1. Business Requirement<br>
2. KPIs Requirements<br>
3. Chart Requirements<br>
4. Dataset<br>
5. Installation<br>
6. Data Preprocessing<br>
7. Analysis and Visualizations<br>
8. Results<br>
9. Contributing<br>
10. Contact Information<br>
11. License<br>

### 1.Business Requirement<br>
The primary objective of this project is to conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and<br> inventory distribution to identify key insights and opportunities for optimization. This is achieved by calculating various KPIs <br>and generating insightful visualizations using Python.<br>

### 2.KPIs Requirements<br>
The following Key Performance Indicators (KPIs) were calculated:<br>
• Total Sales: The overall revenue generated from all items sold.<br>
• Average Sales: The average revenue per sale.<br>
• Number of Items: The total count of different items sold.<br>
• Average Rating: The average customer rating for items sold.<br>

### 3.Chart Requirements<br>
The analysis includes the following visualizations:<br>
a) Total Sales by Fat Content:<br>
     Objective: Analyze the impact of fat content on total sales.<br>
     Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.<br>
     Chart Type: Donut Chart.<br>
b) Total Sales by Item Type:<br>
     Objective: Identify the performance of different item types in terms of total sales.<br>
     Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.<br>
     Chart Type: Bar Chart.<br>
c) Fat Content by Outlet for Total Sales:<br>
     Objective: Compare total sales across different outlets segmented by fat content.<br>
     Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.<br>
     Chart Type: Stacked Column Chart.<br>
d) Total Sales by Outlet Establishment:<br>
     Objective: Evaluate how the age or type of outlet establishment influences total sales.<br>
     Chart Type: Line Chart.<br>
e) Sales by Outlet Size:<br>
     Objective: Analyze the correlation between outlet size and total sales.<br>
     Chart Type: Donut/Pie Chart.<br>
f) Sales by Outlet Location:<br>
     Objective: Assess the geographic distribution of sales across different locations.<br>
     Chart Type: Funnel Map (though a bar plot was used in the provided code for this objective).<br>

### 4.Dataset<br>
The analysis uses the blinkit_data.csv dataset. The dataset contains the following columns:<br>
• 'Item Fat Content'<br>
• 'Item Identifier'<br>
• 'Item Type'<br>
• 'Outlet Establishment Year'<br>
• 'Outlet Identifier'<br>
• 'Outlet Location Type'<br>
• 'Outlet Size'<br>
• 'Outlet Type'<br>
• 'Item Visibility'<br>
• 'Item Weight'<br>
• 'Sales'<br>
• 'Rating'<br>

### 5.Installation <br>
To run this analysis, you need to have Python installed along with the following libraries:<br>
• 'pandas'<br>
• 'numpy'<br>
• 'matplotlib'<br>
• 'seaborn'<br>

### 6.Data Preprocessing <br>
The following data preprocessing steps were performed:<br>
• Loading Data: The blinkit_data.csv file is loaded into a pandas DataFrame.<br>
• Standardizing 'Item Fat Content': The Item Fat Content column had inconsistent values ('low fat', 'LF', 'reg'). These were standardized<br> to 'Low Fat' and 'Regular'.<br>

### 7.Analysis and Visualizations<br>
#### A) KPI Calculations<br>
The following KPIs were calculated and printed:<br>
• Total Sales: $1,201,681<br>
• Average Sales: $140.99<br>
• No of Items Sold: 8,523<br>
• Average Ratings: 4.0<br>

#### B) Charts Generated<br>
a) Total Sales by Fat Content (Donut Chart)<br>
Shows the proportion of sales contributed by 'Regular' and 'Low Fat' items.<br>
b) Total Sales by Item Type (Bar Chart)<br>
Displays total sales for each item type, sorted in descending order.<br>
c) Fat Content by Outlet for Total Sales (Stacked Column Chart)<br>
Compares total sales across different Outlet Location Types, segmented by Item Fat Content.<br>
d) Total Sales by Outlet Establishment (Line Chart)<br>
Illustrates the trend of total sales over Outlet Establishment Year.<br>
e) Sales by Outlet Size (Pie Chart)<br>
Shows the distribution of total sales across different Outlet Size categories.<br>
f) Sales by Outlet Location (Bar Plot)<br>
Visualizes total sales for each Outlet Location Type, sorted in descending order.<br>

### 8.Results<br>
The analysis provides insights into:<br>
• The contribution of different fat content categories to overall sales.<br>
• The best-performing item types in terms of sales.<br>
• How sales of regular vs. low-fat items vary across different outlet locations.<br>
• The sales performance trend based on the establishment year of outlets.<br>
• The impact of outlet size on total sales.<br>
• The geographic distribution of sales across different outlet locations.<br>
These insights can be used to optimize inventory, improve customer satisfaction strategies, and enhance sales performance.<br>

### 9.Contributing<br>
Feel free to fork this repository and contribute by improving the analysis, adding more visualizations, or enhancing the code.<br>

### 10.Contact Information<br>
For any questions or inquiries, please contact:<br>
• Name: NeerajSharma1508<br>
• Email: neerukct15@gmail.com<br>
• LinkedIn: [https://www.linkdin.com/](https://www.linkedin.com/in/ineerajsharma15/)<br>

### 11.License<br>
This project is licensed under the MIT License. See the LICENSE file for details.<br>
