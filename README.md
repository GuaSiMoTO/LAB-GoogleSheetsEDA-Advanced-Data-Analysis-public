# LAB-GoogleSheetsFDA-Advanced-Data-Analysis

![Student LAB](https://images-ext-1.discordapp.net/external/dkBicrHzUxUqUh-WDRAkj8VQIBL8ggLQGcro1kmaSHA/https/res.cloudinary.com/edukami-staging/image/upload/v1739975930/labImages/cuerdenwd29wgrvn4m0j.png?format=webp&quality=lossless&width=1391&height=288)

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

The goal of today's exercise is to analyze and visualize sales data using advanced techniques in Google Sheets. You will be provided with a dataset from a retail company and guided through several tasks to build your data analysis and visualization skills.

## Scenario

You are working as a data analyst at RetailCo, a company that sells various electronic products and office supplies. Your manager has asked you to analyze the sales data from the past year to identify trends and insights that can help improve the company's sales strategy.

## Dataset

You will be working with a dataset named `RetailCo_Sales_Data.csv`. This dataset contains the following columns:

- Order ID
- Product
- Category
- Sales Amount
- Cost
- Profit
- Date of Sale
- Region

### Iteration 1: Data Analysis Essentials

1. **Load the Data**
   - Import the RetailCo_Sales_Data.csv file into Google Sheets. You can do this by opening Google Sheets, selecting File > Import > Upload, and choosing the file.
   - Familiarize yourself with the dataset by browsing through the columns and rows.

2. **Data Cleaning**
   - Check for any missing values and handle them appropriately.
   - Ensure that all numerical data is in the correct format (e.g., Sales Amount, Cost, Profit should be numbers with two decimal places).


If you encounter any product without its corresponding category, use the following reference table to identify the correct category for each product.

| Product   | Category       |
|-----------|----------------|
| Laptop    | Electronics    |
| Mouse     | Electronics    |
| Keyboard  | Electronics    |
| Printer   | Accessories    |
| Monitor   | Accessories    |

### Iteration 2: Pivot Table Proficiency
1. **Create Pivot Tables**
   - Create a Pivot Table to summarize the sales amount by region and category.
   - Create another Pivot Table to summarize the total profit by region and product.

2. **Customize the Pivot Tables**
   - Organize each Pivot Table to display the data in a visually appealing manner.
   - Ensure that each Pivot Table has appropriate row and column headers, and that the data is formatted correctly.

### Iteration 3: Advanced Charting with PivotCharts

1. **Create PivotCharts**
   - Visualize the sales amount by region and category using a PivotChart based on the first Pivot Table created in Iteration 2.
   - Create another PivotChart to visualize the total profit by region and product using the second Pivot Table created in Iteration 2.

2. **Customize the PivotCharts**
   - Modify the chart types and add data labels to enhance the charts' readability and presentation.

### Iteration 4: Detailed Sales and Performance Analysis

1. **Analyze Sales Performance**
   - Analyze the total sales amount and profit for each product category.
   - Determine which product category is the most profitable and which one generates the most sales.

2. **Analyze Regional Performance**
   - Compare the sales performance across different regions.
   - Identify which region has the highest and lowest sales and profits.

3. **Identify Seasonal Trends**
   - Analyze the sales data to identify any seasonal trends.
   - Determine which months have the highest and lowest sales and profits.

### Iteration 5: Utilizing Google Sheets Analytical Tools

- **Analyze Data with Data Analysis Toolpak**
   - Perform a regression analysis to understand the relationship between cost and profit using the XMLiner Analysis Toolpak.

### Bonus Iteration: Analyzing London Weather Data

In this bonus iteration, you will analyze weather data from London. The dataset `london_weather.csv` contains the following columns (adjust these based on the actual columns in your dataset):

- Date
- Temperature (C)
- Precipitation (mm)
- Wind Speed (km/h)
- Humidity (%)

1. **Load the Data**
   - Open the `london_weather.csv` file in Google Sheets.
   - Familiarize yourself with the dataset by browsing through the columns and rows.

2. **Data Cleaning**
   - Check for any missing values and handle them appropriately.
   - Ensure that all numerical data is in the correct format (e.g., Temperature, Precipitation, Wind Speed, Humidity should be numbers with two decimal places).

#### Analysis Hints

2. **Temperature Trends**
   - Consider how temperature varies over time. Are there noticeable patterns or anomalies?
   - Think about how you could use charts to visualize these trends.

3. **Precipitation Patterns**
   - Reflect on the distribution of precipitation across different times of the year.
   - What months or seasons have unusually high or low precipitation?

4. **Wind Speed Analysis**
   - Examine the wind speed data for significant variations or outliers.
   - How could you summarize and visualize the distribution of wind speeds?

5. **Humidity Levels**
   - Look for trends in humidity over time.
   - How does humidity compare across different months or seasons?

![Happy Coding](https://images-ext-1.discordapp.net/external/yCS9e-T4ZqwyrDeKZivDFuwoXfN2h5eWdr9eg6YedlU/https/res.cloudinary.com/edukami-staging/image/upload/v1739975973/labImages/dytxhbiiyolvrbgipq4x.png?format=webp&quality=lossless&width=1391&height=288)
