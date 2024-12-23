# Cooking-and-Order-Trends
# Data Analytics Assignment: Cooking and Order Trends

## Objective
The objective of this assignment is to analyze user behavior, cooking preferences, and order trends to uncover insights and provide actionable business recommendations.

## Datasets
### 1. UserDetails.csv
- Contains user demographic and registration information.
- **Key Fields**: User_ID, Age, Location, Favorite_Meal, Total_Orders.

### 2. CookingSessions.csv
- Logs details of cooking sessions conducted by users.
- **Key Fields**: Session_ID, Dish_Name, Meal_Type, Session_Rating.

### 3. OrderDetails.csv
- Tracks user orders, their statuses, and associated ratings.
- **Key Fields**: Order_ID, Dish_Name, Amount (USD), Order_Status.

## Process
1. **Data Cleaning**: Standardized column names and ensured consistent formats.
2. **Data Merging**: Combined datasets using `User_ID` and `Session_ID`.
3. **Analysis**: Explored the relationship between cooking sessions and orders, identified popular dishes, and analyzed demographic influences.

## Steps for Visualization and Analysis in Excel
### 1. Analyze Popular Dishes
- Use a pivot table to count the frequency of each dish (`Dish_Name`).
- Sort the results in descending order.
- Create a bar chart to visualize the top 10 popular dishes.

### 2. Analyze Average Session Ratings by Meal Type
- Create a pivot table to calculate the average `Session_Rating` for each `Meal_Type`.
- Use a bar chart to compare the average ratings.

### 3. Analyze Orders by Location
- Use a pivot table to count the number of orders per `Location`.
- Sort the data to identify the top-performing locations.
- Create a bar chart to display the top 10 locations.

## Insights and Recommendations
- **Top Dishes**: Focus on promoting popular dishes to drive engagement.
- **Session Ratings**: Improve meal types with lower ratings to boost user satisfaction.
- **Orders by Location**: Target high-performing locations for promotions and low-performing locations for growth opportunities.

## Files in Repository
1. **Merged_Dataset.xlsx**: Consolidated dataset after cleaning and merging.
2. **README.md**: Description of the assignment and datasets.
3. **Analysis and Visualizations**: Includes findings and charts (to be added).


