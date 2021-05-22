# DATA MANIPULATION, PROCESSING, AND ANALYTICS ON XYZ SUPERMARKET
Company XYZ owns a supermarket chain across, with its major branch located in three(3) cities Abuja, Lagos, and Portharcourt with the following product lines; electrical accessories, Electronic accessories, Home and Lifestyle, Food and beverages, Sports and travel, Health and beauty, Fashion accessories. Descriptive data manipulation, processing, and analysis were performed on the gathered data from all three branches and insights are generated to help understand trends and determine growth.

## Project Steps

In the course of the analysis the following steps were taken before and during the analysis;
1) First, deep study of each description of features in other to understand the concept of the supermarket and point out probably areas of interest of the enterprise towards its growth, development, and deployment of efficient business management and strategies.

2) Secondly, a short statistical summary of the data that was gathered from the three main branches and drew a brief insight of it.

3) Thirdly, checking for missing values and noted the observation and also checked the current state (data-type) of all the columns using the info() attribute

4) Moving on, I performed few breakdowns of some columns that were meant to have been in DateTime format, hence the process of datatype conversion was initiated after which hours, days, weeks, and months were extracted from the DateTime columns to the end that more detailed information about periodical trends are obtained

5) Next, I obtained the unique values in all categorical features.

6) I performed groupby type categorization and aggregation on the data, other columns by city, and other columns

7) Lastly I used matplotlib and seaborn library for the visualization of the data to get inferences from the data. The visualization is compressed into three parts:
          a) Trend Identification
          b) Correlation
          c) Distribution

## Insights
The data properly collated as there were no missing values or outliers

The approximate average unit price and quantity are #20,000 and 6 units respectively making our total sales/revenue to be around #120,000 without incurring tax.
Note: The tax on the supermarket is about 4.5% of the total sales. After accounting for tax the average total value is found to be around #116,000. Knowing that the average cost of goods sold is approximately #110,700 and the gross income is approximately #5,537 it informs us that the average sales made within the timeframe are about #115,000

The average rating is 6.97 indicating that the supermarket is doing slightly better above-average implying that more work needs to be done to improve the companies services and products available to customers

All the data are filled with inputs and hence there are no null or empty data cells in the columns

We can say inferentially that Port Harcourt has the highest total gross income with Abuja being the second and then Lagos.

The city with the highest average rating is and the City with the highest average rating is PortHarcourt with Lagos being the next in line followed by Abuja.

The branch with the highest average rating is and the City with the highest average rating is branch C with branch B being the next in line followed by branch A.

A large percent of the electrical accessories were paid for using the cash channel

For home and lifestyle product lines it was majorly purchased using Epay

There is a fine distribution of the payment channels used for the food and beverages product line

Sports and travel have the majority of their products paid in cash

Most of the customers who purchase health and beauty products were paid with using Epay

A very large amount of the Fashion accessories were paid for using Epay

Food And Beverages are sold most in Port-Harcourt

Fashion accessories are also sold most in Port-Harcourt

Lagos has the highest purchase for electronic equipment

Sports and travel products were mostly sold in Abuja

Home and lifestyle commodities are heavily purchased in Lagos

All three states have an approximately equal number of sales for health and beauty commodities

The supermarket should focus on increasing its marketing strategy for sales of health and beauty products especially in Lagos which has a high potential yield rate

In other for the Branch at Port-Harcourt to do better the sales management should work on generating more incoming through sports and travel, home, and lifestyle commodities.

More efforts need to be put into the Lagos fashion accessory fraction

Relative to Lagos and Port Harcourt Abuja branch hasn't been doing well sales-wise as regards the yield in sales for the food, beverage, home, lifestyle, health and beauty hence more attention should be given to these areas

This indicates that there is a high variance in the correlation between the cost of goods sold and the total amount generated

Dominant female activity in branch A and B while the men seem to be slightly higher than the females at Branch C

## Future Work
In other to make the work look more robust tasks like the following should have been carried out:
a) Exploration of more data visualization tools

b) Predictive Analysis to make a sustainable inference.

c) Collection and addition of more relevant features

d) Addition of more financial columns for a much more economic descriptive analytics

## Standout Section
a) Groupby Categorization of the areas with the most rating

b) Distribution visualization of sales by gender to see the volume of the total amount contributed by respective gender

c) Comparison of other features to an important column 'RATING' which was not given in the project requirement. It is crucial to know the reaction of the branches to respective products and services provided, rating based on the product line.

