# Flipkart Exploratory Data Analysis 📊🔍

## Project Description 📝
This project involves performing an exploratory data analysis (EDA) on the Flipkart dataset. The main goal is to gain insights and understanding from the data to identify patterns, trends, and relationships that can provide valuable information about the products and brands available on Flipkart. 🚀

### Importing Dependencies 📚
The initial step is to import the necessary Python libraries, including Pandas and NumPy for data manipulation, Plotly Express and Graph Objects for data visualization, and Google Colab for mounting the Google Drive to access the dataset. 📈🔢📊

### Loading Dataset 📂
The dataset is loaded from a CSV file stored in Google Drive using Pandas' `read_csv()` function. The first few rows of the dataset are displayed to understand its structure and contents. 📁👀

### Data Preprocessing 🔄
Before proceeding with the analysis, data preprocessing is performed to handle missing values and calculate the discount percentage for each product. The missing values in the 'retail_price', 'discounted_price', 'image', 'description', 'brand', and 'product_specifications' columns are handled appropriately. The discount percentage is calculated as the difference between the 'retail_price' and the 'discounted_price' divided by the 'retail_price', and then multiplied by 100. 🛠️📝

### Data Analysis 📊
The data analysis section covers various aspects of the dataset. 🔍

1. Top Products and Brands Distribution 🥇🏆
A pie chart is used to visualize the distribution of the top products and brands purchased on Flipkart. The top 10 main products and top 10 brands with the highest purchase counts are identified and displayed in the pie chart. 🍰🛍️

2. Brands with High Discounts 💰💯
Brands that offer high discounts are identified and displayed using a bar chart. The mean discount percentage for each brand is calculated, and the top brands with the highest average discount percentages are presented in the bar chart. 📊🎁

3. 5-Star Rating ⭐⭐⭐⭐⭐
The number of products with a 5-star rating is calculated and presented using a funnel plot. The funnel plot illustrates the number of products at each stage, starting from the total number of products to the number of products with ratings and finally the number of products with a 5-star rating. 🏅🎯

4. Ratingwise Count 📈👍
The count of products for each rating level is visualized using a scatter plot. The number of products is displayed on the y-axis against the rating on the x-axis. 📈📉

5. Variation in Discount throughout a Year 📅📈
The average retail price and discounted price are calculated for each date in the dataset, and the variation in prices throughout the year is visualized using an area chart. 📈📉📅

6. User Engagement Pattern throughout the Day ⌚📈
The number of clicks on product URLs is plotted against the time of day using a scatter plot. The plot provides insights into user engagement patterns on Flipkart throughout the day. 🕰️📊

### Conclusion 📝🎉
The exploratory data analysis of the Flipkart dataset has provided valuable insights into product and brand trends, user engagement, and pricing patterns. The findings can be used to optimize marketing strategies, identify popular products and brands, and understand user behavior on the platform. 📈💼🧠
