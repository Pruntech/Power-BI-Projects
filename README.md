# Project Name: Chocolate Store Sales


## Objective:
This Power BI project was designed to provide a comprehensive view of the sales performance for a chocolate store by integrating data from a local MySQL database and creating an interactive dashboard for performance analysis.


## Steps Taken:

### Database Integration:
Integrated a local MySQL database with the Power BI project, enabling seamless data import for analysis.\
Database includes:
- (Date Dimension Table) Calendar table
- (Dimension Table) Geographical table
- (Dimension Table) Employees information table
- (Dimension Table) Products information table
- (Fact Table) Sales table

### Data Modeling:
Using Power Query, I validated the data, cleaned it, corrected missing values and removed unnecessary columns.\
In Power BI, I set up relationships and developed a star schema to optimize the data model for reporting.

### Dashboard Creation:
The following key dashboards were created to provide insights into sales performance:

### KPI Dashboard:
Displays two main KPIs: Profit (Revenue - Boxes Cost) and Profitability (Profit / Boxes Count) - Overall and broken down by teams.\
We can see status of our KPIs by last of selected months - current value vs target.

### Profit Dashboard:
Shows the company’s profit, segmented by date range (months/years), teams, salespeople, and products.\
Allows detailed insight into company profits.

### Profitability Dashboard:
Displays profitability, calculated as profit per unit sold, with the ability to filter by date range (months/years), teams, salespeople, and products.\
Allows to check the status of company profitability.

### Overall Dashboard:
Tracks the sales (Revenue) trend by date (month/year), comparing sales to the previous year. It also displays product profit vs costs comparison and customer trends by date (month/year).

### Products Dashboard:
Identifies the most and the worst profitable products within a selected time period, highlighting the top 3 best-performing products, their sales quantities, and the number of customers who purchased each.

### People Dashboard:
Shows the performance of individual teams and their members, including the highest-grossing team, the team with the highest average profit per person, and the top-performing salesperson.

### Map Dashboard:
Visualizes profit and customer numbers by country, providing insights into regional performance.


### Additional Features:
Each dashboard includes a Navigator for easy navigation between views and a Slicer for filtering data by year and month.\
Interactions between visualizations have been configured to enhance the intuitiveness of data drilling, allowing users to smoothly explore different levels of detail.




# Project Name: HR Dashboard


## Objective:
This Power BI project was designed to provide a comprehensive view of key HR metrics by integrating data from multiple Excel files, enabling data-driven workforce management and decision-making.


## Steps Taken:

### Data Integration:
Imported and combined data from multiple Excel files, including:
- (Fact Table) Employee information table
- (Dimension Table) Geographical table for office locations
- (Dimension Table) Employee survey results

### Data Modeling:
Power Query: Validated data accuracy, cleaned and corrected missing values and removed unnecessary columns.\
Power BI: Established relationships between tables and created a star schema to optimize performance.

### Dashboard Creation:
Developed multiple interactive dashboards to analyze key HR metrics:

### Home Dashboard:
Provides an overview of workforce demographics, including:\
- Number of all and new employees
- Total number and percentage of employees by gender
- Total number and percentage of employees by employment status (active or resigned)
- Age distribution
- Total number of employees by office locations
- Total number of employees by years of service

### Office Score Dashboard:
Compares office performance across key HR indicators, such as:\
- Average performance rating
- Average job satisfaction
- Average monthly salary
- Employee attrition rate

### Survey Results Dashboard:
Displays employee survey results overall and for each office and compares them to predefined targets.

### Attrition Key Influences Dashboard:
Analyzes factors contributing to employee attrition, such as:\
- Survey responses
- Age and income
- Maritial status
- Overtime hours
- Tenure at the company
- Total working Years
- Performance rating


### Employees Dashboard:
Provides insights into individual employees, including:\
- Performance rating
- Job satisfaction
- Years since last promotion
- Monthly salary
- This enables HR to assess employees for potential promotions or salary adjustments.

### Additional Features:
Each dashboard includes a Navigator for seamless navigation and Slicers for filtering by office, department, and job position.\
Interactions between visualizations have been configured to enhance the intuitiveness of data drilling, allowing users to smoothly explore different levels of detail.\
Additionally, this setup can be used to implement security measures, ensuring that users from a specific office and department can only access data relevant to their assigned scope.

