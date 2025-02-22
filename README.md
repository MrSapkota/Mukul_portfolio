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



# [Project 7: Pizza Hut Database Management System](https://github.com/MrSapkota/Pizza_Sales_SQL/tree/main)


Designed and implemented a relational database system for Pizza Hut to manage orders, track sales, and analyze revenue. Developed advanced SQL queries to generate daily revenue reports, cumulative revenue trends, and pizza-type performance analysis. Demonstrated expertise in database design, query optimization, and data analysis.

Key Achievements:

Created a normalized database schema for efficient data storage and retrieval.
![image](https://github.com/user-attachments/assets/e8b3d21c-d5f0-4fd0-9609-7f43799ef31d)

Developed complex SQL queries using window functions, joins, and aggregations.

![image](https://github.com/user-attachments/assets/07a89dd3-e416-4840-a8a8-888037968a51)

![image](https://github.com/user-attachments/assets/5d3f7385-e437-4178-95d7-6eca60b7c199)



Delivered actionable insights to optimize menu offerings and pricing strategies.
![image](https://github.com/user-attachments/assets/7c7f33cd-712c-47ec-980a-8cdde0e2a806)

![image](https://github.com/user-attachments/assets/7351178c-dd2a-4cd1-ace9-e21b2e7e2ac1)



# [Project 8: Exploratory Data Analysis & logistic regression on titanic dataset](https://github.com/MrSapkota/EDA_Titanic_dataset/tree/main)

The Titanic dataset provides a fascinating opportunity to analyze passenger demographics and understand the factors influencing survival in the tragic sinking. In this project, I performed exploratory data analysis (EDA) to gain insights into this historical event and prepare the data for predictive modeling. I leveraged Python libraries such as Pandas, Matplotlib, and Seaborn for data manipulation and visualization.

Data Understanding

My initial step involved gaining familiarity with the dataset's structure and contents. Using functions like head(), info(), and describe(), I examined the first few rows, data types, missing values, and summary statistics of various features.

df.head() output displaying the first few rows and columns.
![image](https://github.com/user-attachments/assets/fa60b903-23a1-47ac-90ca-6aece73a13ac)

Screenshot 2: Output of df.info() showing data types and missing values.
![image](https://github.com/user-attachments/assets/371cec37-bcb4-4110-9dbe-44eaaadb4c36)

Screenshot 3: Output of df.describe() providing descriptive statistics for numerical feature
![image](https://github.com/user-attachments/assets/2fc02280-e37a-4133-8d55-f6957b6ef130)

Data Cleaning

Data quality is crucial for accurate analysis. I identified and addressed missing values in columns like 'Age', 'Cabin', and 'Embarked'. For numerical features like 'Age', I employed imputation using the mean or median. For categorical features like 'Embarked', I used the mode for imputation.

 Code snippet demonstrating imputation techniques (e.g., filling missing 'Age' with the mean).
 ![image](https://github.com/user-attachments/assets/a53d75ed-b043-4109-815e-9020360880be)
![image](https://github.com/user-attachments/assets/8c4498a3-1c79-4a1b-98bf-fc3005035a15)
![image](https://github.com/user-attachments/assets/9ab71f32-786c-43ec-916a-3f4f9172edf6)

Screenshot 5: Output of df.isnull().sum() after cleaning, showing no missing values.

![image](https://github.com/user-attachments/assets/8f6a8b24-44c9-47a6-aaa3-571e7b1798d8)


Univariate and Bivariate Analysis

To uncover patterns and relationships within the data, I performed univariate and bivariate analyses using various visualizations.

Histogram or count plot showing the distribution of the target variable 'Survived'.
![image](https://github.com/user-attachments/assets/5cd0f72e-107c-45ef-8908-da05cc498eea)

Count plots or bar charts comparing survival rates across different categories like 'Pclass' (passenger class) and 'Sex'.
![image](https://github.com/user-attachments/assets/2295010d-f414-4ecf-aa7a-b7179191aa08)

 Scatter plot illustrating the relationship between numerical features like 'Age' and 'Fare'.

![image](https://github.com/user-attachments/assets/294668b5-dc7e-4365-b0ca-6a20f6db5d98)

![image](https://github.com/user-attachments/assets/3e7f7c94-38e5-416b-ac8a-24a81b2f019f)

Logistic Regression Model

![image](https://github.com/user-attachments/assets/0dd26c04-22f3-4635-8cd0-6c2df9e4cfc5)
![image](https://github.com/user-attachments/assets/d9d1a2ab-4699-473b-94c3-f8db4373d449)

Model Evaluation and Insights

![image](https://github.com/user-attachments/assets/d6c74827-08c3-4f6b-9152-594e2f28cb29)

![image](https://github.com/user-attachments/assets/dc0b8287-b561-455d-9f14-95dc92ce51e9)

Key Findings and Insights

Through the EDA process, I unearthed valuable insights regarding passenger survival:

Passenger Class: Passengers in higher classes (1st and 2nd) had a significantly higher survival rate compared to those in 3rd class. This observation suggests a correlation between socioeconomic status and survival.
Gender: Female passengers had a much higher survival rate than male passengers. This finding reflects the "women and children first" protocol followed during the evacuation.
Age: Age played a role in survival, with children and younger adults having a higher likelihood of survival.

Conclusion

This EDA provided valuable insights into the factors influencing passenger survival on the Titanic. By cleaning the data, visualizing patterns, and exploring relationships between variables, I prepared the dataset for machine learning modeling. Further steps could include feature engineering, model selection, and evaluation to develop predictive models for survival based on passenger characteristics. I believe this project demonstrates my proficiency in data analysis, visualization, and storytelling. It highlights my ability to extract meaningful insights from complex datasets and prepare data for further analysis and model building.


# [Project 9: Netflix Dashboard Visualizaton (Tableau)](https://github.com/MrSapkota/Netflix_Analysis_Tableau)

📊 Netflix Dashboard Visualization (Tableau)
Overview:
Developed an interactive Netflix Dashboard in Tableau to analyze and visualize Netflix's content library, offering insights into movies and TV shows based on year, genre, country, and ratings.

Key Features:

🌍 Global Content Distribution: Mapped total movies & TV shows by countries.
🎬 Content Breakdown: Visualized the distribution between movies (68.42%) and TV shows (31.58%).
📅 Yearly Trends: Highlighted the growth of Netflix’s library over time.
📈 Top 10 Genres: Showcased popular genres like Documentaries, Stand-Up Comedy, and Dramas.
⭐ Ratings Analysis: Breakdown of content ratings (e.g., TV-MA, TV-14).
⏱ Duration & Release: Insights on show durations and release years.
📝 Dynamic Descriptions: Interactive details for individual movies/TV shows.
Tools Used:

Tableau for data visualization
Python (optional) for data preprocessing
Netflix Titles Dataset
💡 Insights:

Significant rise in Netflix’s content post-2015.
U.S. dominates the content library, followed by India and the U.K.
Documentaries and Stand-Up Comedy are among the top genres.

![image](https://github.com/user-attachments/assets/798d442c-0440-423d-8a21-c4924c7491f6)






