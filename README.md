# Atliq Hotel Analysis Project -- Python

## **Problem Statement:**

Atliq Grands, a leading player in India's hotel industry, is currently facing challenges with rising competition and declining revenue. The company is also experiencing a loss of market share. To combat these challenges, the management team has decided to harness data and strategic insights. With limited internal expertise in data analysis, they have sought external support to assess the situation, deliver actionable insights, and develop effective strategies for customer retention and revenue growth.

## **Project Goal:**

The goal of this project is to conduct a comprehensive analysis of the hotel industry domain using Python. By leveraging data-driven insights and strategic recommendations, the objective is to empower Atliq Grands to make informed decisions. The ultimate aim is to assist Atliq Grands in regaining a competitive edge in the market, addressing their challenges of revenue decline and market share loss effectively.

## **Datasets:**
- dim_date.csv
- dim_hotels.csv
- dim_rooms.csv
- fact_bookings.csv
- new_data_august.csv
- fact_aggregated_bookings.csv

## **Data Analysis Process:**
1. Data Import & Exploration
2. Data Cleaning
3. Data Transformation
4. Data Insights
5. Key Insights Summary
6. Recommendations

- Data Import & Exploration: We started by importing datasets such as bookings, hotels, and room categories. Initial exploration helped in understanding the structure and quality of the data.
  
- Data Cleaning: Addressed missing values, removed outliers, and corrected data inconsistencies to ensure accurate analysis.
  
- Data Transformation: Created new variables like occupancy percentage to facilitate deeper analysis. This step also involved merging datasets for a comprehensive view.
  
- Data Insights & Visualization: Key metrics like occupancy rate, revenue realized, and booking patterns were analyzed and visualized using Python libraries.
  
- Summary & Recommendations: The analysis provided actionable insights which were summarized and included strategic recommendations to address the identified challenges.

# Tools & Functions Used:
- Pandas: Data manipulation and analysis, including groupby, merge, and describe.
- Matplotlib: Visualization of data insights through bar charts, pie charts, and line plots.
- NumPy: Handling numerical operations and creating new variables like occupancy percentage.
- Data Cleaning Techniques: Addressed missing data, corrected formats, and removed outliers to ensure data quality.

# Key Insights
**Average Occupancy by Room Type**

- Presidential rooms have the highest average occupancy (59.30%).
- Elite and Premium rooms have the lowest average occupancy (58.03% and 58.04%).

 **Average Occupancy Rate per City**

- Delhi has the highest average occupancy rate (61.61%).
- Bangalore has the lowest average occupancy rate (56.59%).

 **Weekday vs. Weekend Occupancy**

- Occupancy is significantly higher on weekends (72.39%) compared to weekdays (50.90%).

 **Occupancy Rates in June**

- Delhi had the highest occupancy in June (62.47%).
- Bangalore had the lowest occupancy in June (56.58%).

 **Revenue Realized per City**

- Mumbai generates the highest revenue (`$668,569,251`).
- Bangalore generates the lowest revenue (`$420,383,550`).

 **Revenue by Hotel Type**

- Atliq Exotica has the highest revenue (`$32,436,799`).
- Atliq Seasons has the lowest revenue (`$6,672,245`).

 **Average Rating per City**

- Delhi has the highest average rating (3.79).
- Bangalore has the lowest average rating (3.41).


# Recommendations

**1. Promote Less Popular Room Types and Cities**

- Use targeted promotions and partnerships to boost occupancy in less popular room types and cities.

**2. Enhance Weekday Occupancy**

- Create attractive weekday offers and corporate partnerships to balance occupancy rates.

**3. Adjust Strategies Based on Revenue and Ratings**

- Focus on cities and hotel types with lower revenue and ratings for targeted improvements.

**4. Utilize Data for Decision-Making**

- Regularly integrate and analyze new data to make informed decisions and forecasts.

**5. Improve Customer Satisfaction**
   - Invest in training and resources to enhance guest experience, particularly in cities and hotel types with lower average ratings.

**6. Optimize Marketing Efforts**
   - Tailor marketing campaigns based on historical data to effectively target high-potential markets and improve overall occupancy and revenue.

## Key Learnings
- Data Cleaning: Identifying and handling outliers and inconsistencies is crucial for accurate insights.

- Visualization: Effective use of Python’s visualization libraries (Matplotlib, Pandas) is key to presenting data in an understandable format.

- Strategic Analysis: Merging datasets and creating new metrics can uncover hidden patterns that are crucial for decision-making.

# Conclusion
This project was a great learning experience in applying data analysis techniques to solve real-world business problems. The insights gained have the potential to drive strategic decisions and improve business outcomes for Atliq Grands.


