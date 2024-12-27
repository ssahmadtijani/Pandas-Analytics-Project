NB: This is a template to make documentation process easy. You can remove the `To-Do` notes in your final commit

# Company XYZ Supermarket Sales Analysis

Analysis of sales across cities

# Project Steps

- I used the glob method to get all csv files.
- I read the data in the combined files into a variable.
- Using the `info` function, I was able to see the data type and the number of `non-null` values in the data.
- I used the `to_datetime` function to convert the date and time functions which were initially in string format to to_datetime
- I used the `dt.day`, `dt.month`, `dt.year`, `dt.hour` attirbute to get the day, month, year and hour respectively.
- I used the `dt.hour.nunique()` method to get the number of unique values for the hour and I used the ``dt.hour.unique()` method to get the unique hours as an array
- I used the `unique()` method to get the unique values for the other columns
- I used the `value_counts()` method to get the number of occurences for values for each column
- I used the `groupby` to get group the record set by city
- I used the `sum()` nethod of the groupby object to sum the numeric columns, the `max()` method to get the maximum
- For data visualization, I set the size to `8,6`
- I created a `countplot` with `Branch` as the x axis ordered by `Branch` to see a plot of number of sales per Branch
- I used the `countplot` to see the number of sales per product line with product line on the y axis giving me an horizontal chart
- I further broke down the product line sales into the payment type using `countplot` with payment set as the `hue`
- I created a `countplot` with payment as x axis and the Branch as the `hue` to show the number of times a payment type is used by each branch
- I used the `boxplot` to show the ratings per branch and detertmine the branch with the lowest rating.
- Using the `catplot`, I was able to show each product line and the quantity bought by each gender. This helped determine which product are likely to be bought by eacch gender.
- Using the `catplot`, I was able to show each product line and the total amount spent by each gender. 
- Using the `catplot`, I was able to determine the reltionship between the product category and the unit price. 
- Using the `catplot`, I was able to determine the reltionship between the product category and the quantity bought. 
- Electronic accessories have the highest number of cash payment.
- Fashion accessories are the most bought items.
# Insights

- Fashion accessories are the least purchased and are also the most expensive.
- Also, Electronic accessories are the most bought and are also the cheapest.
- Women spent more money on Food and Beverages than men
- Interestinglly, Men, spent more money on health and beauty products than women
- Women bought more sports and travel items than men but men spend more money on sports and travel material than women
- Abuja has the lowest rating
- There is more epayment usge in Lagos than other cities, while, Port Harcourt has more cash usage than other cities. Abuja leads the way with Card usage

# Future Work

- I want to see the gender that contributed to Branch B having the lowest rating. 
- I also want to see the products and prices that led to the low rating for Branch B

# Standout Section

I set different aspect and height to make the visualization compact

# Executive Summary.

Given that the products with the lowest price have the highest patronage, you could have discount on other products to drive up patronage.
