# Mukul_portfolio
Analytics Portfolio

# [Project: 1 - Predictive Analytics Using Python](https://github.com/MrSapkota/World-Population-Data-Visulaization-with-Python)
Description: This project, completed during my Master's degree, focused on predictive analytics using machine learning techniques.

Key Contributions:

Analyzed five global datasets on population metrics, including height, weight, IQ, life expectancy, population density, and quality of life.
Preprocessed data by handling missing values, scaling features, and performing exploratory data analysis.
Engineered features to uncover relationships, such as BMI vs. life expectancy and population density vs. quality of life.

![image](https://github.com/user-attachments/assets/bfa1066c-ae27-418b-a23f-c212e520ebeb)




# [Project: 2 - Weather Prediction Near Heathrow Airport](https://github.com/MrSapkota/weather-station-near-Heathrow-airport-in-London-By-Python)
Description: This project, completed during my Master's degree, focused on predicting maximum temperature using regression and classification techniques with Python.

Key Contributions:

Data Analysis: Analyzed a weather dataset with 10 attributes, including cloud cover, sunshine, global radiation, and temperature measurements.

Linear Regression: Built models using OLS and Gradient Descent methods to predict max temperature. Achieved 87% variance explanation with minimal mean squared error (MSE).

Logistic Regression: Applied binary and multinomial classification to categorize temperatures into hot, moderate, and cold. Achieved 92% accuracy in binary classification.

Feature Engineering: Performed data scaling, feature selection, and transformed target variables for classification tasks.

Visualization: Used heatmaps, plots, and confusion matrices to interpret relationships and model performance.

![image](https://github.com/user-attachments/assets/83422eaf-cd0c-4a76-809e-ffa19c563630)



# [Project 3: Virgin Australia Performance Analysis](https://github.com/MrSapkota/Australian-Airline.)

During my master's degree, I analyzed Virgin Australia's flight performance using Tableau and Python. The project focused on identifying trends, patterns, and operational inefficiencies. Key visualizations included heat maps, scatter plots, and geo-visualizations to highlight on-time performance, cancellations, and route efficiency. I developed interactive dashboards to provide actionable insights, improving operational efficiency and customer satisfaction.

![image](https://github.com/user-attachments/assets/b80f20d0-d208-4831-809f-035c42da2358)


# [Project 4: Super Store Sales Analysis](https://github.com/MrSapkota/pizza_sales_report_powerbi_-_SQL)

For personal learning, I developed a Power BI dashboard to analyze sales trends in an US general store. The project involved visualizing key metrics like revenue, product performance, and customer demographics to derive actionable business insights.

![image](https://github.com/user-attachments/assets/04f4c1b1-c4f8-41c6-bd57-774f82d370a0)


# [Project 4: Pizza Sales Analysis Report](https://github.com/MrSapkota/pizza_sales_report_powerbi_-_SQL)

For personal learning, I created a Power BI report analyzing pizza sales trends from January to December. Key metrics included total revenue, average order value, and best/worst sellers. Using SQL queries, I analyzed daily and monthly sales trends, top-selling pizza categories, and identified opportunities for growth through targeted promotions and inventory optimization.
![image](https://github.com/user-attachments/assets/71e8d342-9f8b-478b-ade0-27b0ba6bafef)


# [Project 5: Music store data analysis using ms sql](https://github.com/MrSapkota/Music-store-dataset)

Analyzed a music store dataset using SQL to derive insights such as top-selling artists, most popular genres by country, and customers with the highest spending. Demonstrated advanced SQL skills, including joins, aggregations, subqueries, and CTEs.
Key Features
Explored a relational database with tables like Customer, Invoice, Track, Album, Artist, and Genre.

Wrote complex SQL queries to analyze data and generate insights.

Used Microsoft SQL Server (MS SQL) for query execution.

Technologies Used
SQL
Microsoft SQL Server (MS SQL)

Example Query
WITH popular_genre AS (
    SELECT 
        customer.country,
        genre.name AS genre_name,
        COUNT(invoice_line.quantity) AS purchases,
        ROW_NUMBER() OVER (PARTITION BY customer.country ORDER BY COUNT(invoice_line.quantity) DESC) AS RowNo
    FROM invoice_line
    JOIN invoice ON invoice.invoice_id = invoice_line.invoice_id
    JOIN customer ON customer.customer_id = invoice.customer_id
    JOIN track ON track.track_id = invoice_line.track_id
    JOIN genre ON genre.genre_id = track.genre_id
    GROUP BY customer.country, genre.name
)
SELECT 
    country,
    genre_name,
    purchases
FROM popular_genre
WHERE RowNo = 1
ORDER BY country;

![image](https://github.com/user-attachments/assets/f5af9d55-4be0-4b54-8fc7-038a96cc05d1)


# [Project 6: Diwali_Sales_Analysis_Using_Python](https://github.com/MrSapkota/Diwali_Sales_Analysis_Using_Python)

In this project, I delved into Diwali sales data to uncover customer behavior and sales trends during the festive season. Using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn, I explored various factors influencing sales, including demographics, location, occupation, and product categories. Through data visualization and analysis, I identified key customer segments, popular products, and regional variations in sales. The insights gained from this project could be used to inform targeted marketing campaigns, optimize inventory management, and improve product development strategies for future Diwali seasons.

Key Findings

Most buyers were female, contributing to 65% of total sales.
![image](https://github.com/user-attachments/assets/6715d0bf-31cc-4188-bef9-6dc01ee6bb28)

The age group of 26-35 years was the most active customer segment.

![image](https://github.com/user-attachments/assets/4f834e36-4b99-4119-8370-02db501d2555)

Sales were concentrated in UP, Maharashtra, and Karnataka, accounting for 40% of total revenue.

![image](https://github.com/user-attachments/assets/7883a24d-11b5-4196-b3a0-3a20df1ab4ea)

Food, clothing, and electronics were the top-selling categories.

![image](https://github.com/user-attachments/assets/a6d16e37-9fb7-4160-a451-276158b301ed)


