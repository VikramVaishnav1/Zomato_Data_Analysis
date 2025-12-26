# Zomato_Data_Analysis
Analyzing data from Zomato can provide significant insights into restaurant trends, customer preferences, and the food industry as a whole. Zomato is a renowned platform for discovering restaurants and ordering food online, and it accumulates a vast amount of data that can be utilized for various types of analysis.

Data Extraction - We have extracted data from Kaggle, a platform that provides various datasets for data analysis. The data we have downloaded is about 850 restaurants listed on Zomato, a popular online food delivery and restaurant discovery platform. This dataset includes comprehensive details about restaurants such as their names, locations, ratings, cuisines, pricing, and more. This data is useful for market research, data analysis, and gaining insights into the restaurant landscape in different cities.
Our data contains 12 columns, including Restaurant Name, Dining Rating, Delivery Rating, Dining Votes, Delivery Votes, Cuisine, Place Name, City, Item Name, Best Seller, Votes, and Prices.



2. Data Cleaning - We began by importing essential libraries such as numpy, pandas, matplotlib, and seaborn. Next, we loaded our dataset and checked for null values. We discovered that the dining rating, delivery rating, and best seller columns contained null values. Upon calculating the percentage of null values for each attribute, we found that the best seller column had a staggering 77 percent null values. Therefore, we decided to drop the best seller column as it contained more than 50 percent null values. We also filled the null values in the delivery and dining ratings columns with their mean value. To further clean the data, we removed duplicate values from the dataset. We then created a new attribute, average rating, by taking the arithmetic mean of the dining rating and delivery rating columns. Finally, we exported the preprocessed and cleaned data into a new CSV file that we created.


3. Visualization in python -
  We used the value counts function to count the unique cities and unique food item names. Then, we plotted the pie chart of the top 10 cities with the most number of restaurants using Matplotlib. We found out that Hyderabad has the most restaurant chains, followed by Mumbai and Chennai.

Next, we plotted a bar chart of the top 5 most ordered food items across cities using Matplotlib. We discovered that Veg fried rice is the most popular dish ordered on Zomato, followed by paneer butter masala, Jerra Rice, chicken fried rice, and French fries.

After analyzing the correlation between prices and different attributes, we found that prices are more correlated with average ratings. If the average ratings are high, the prices of the items are high. Higher-priced food items are usually good in nutrition, quality, and most importantly, tasty. That's why the ratings of these items are high.

Finally, we plotted the bar chart of different restaurants and found out the top 5 biggest food chain with the most number of restaurants in these cities. McDonald's food chain has the most number of restaurants, followed by Fresh Menu, Burger King, Pizza Hut, and Dominos.


4. Viusalization In Tableau -
    I have noted the following information:

1. In Dashboard 1, we have added two new bar charts showing the top 10 restaurants in Hyderabad and Mumbai. The restaurants Exotica and Chaitanya are the highest rated in Hyderabad and Mumbai respectively. The restaurants are sorted in decreasing order of average ratings.

2. We have done the same for Chennai, Bangalore, and Jaipur. Toscano, Truffles, and Thali and more are the highest rated restaurants in terms of the average rating given by customers in Chennai, Bangalore, and Jaipur respectively.

3. In Dashboard 3, we have plotted a graph representing the top 10 cuisines. Beverages top the list, followed by pizza and fast food.

4. Additionally, we have plotted a double-axis graph of average rating and average price of veg fried rice, which is the most popular dish between different cities. We can clearly see that the price of veg fried rice is almost the same in different cities. Therefore, we plotted the lower the gap between the average rating and price, the better it is for the customer. This means that the food is of high quality and taste, and the price is reasonable. After observing, we concluded that Ahmedabad, Mumbai, and Pune have better quality of veg fried rice at a reasonable price.

   
