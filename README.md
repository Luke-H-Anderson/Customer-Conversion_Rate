# Customer Conversion Rate
This is the second project I created while earning my certificate at TripleTen.

While there are several parts of the project, the three main ones that I'd like to demo are 
the cohort analysis, retention rates, and conversion funnel.

# Cohort Analysis

This is a pivot chart that measures the number of specific customers based on their first purchase month 
as specified by the column, and how long customers stay in that cohort, measured in months, as long as they 
continue to make a purchase with the company.

![Cohort Analysis Pivot Table](https://github.com/Luke-H-Anderson/Customer-Conversion_Rate/blob/main/Cohort%20Analysis.png)

For example: Notice in the very first cohort, which starts in September of 2020, there are 32 customers, 
which means 32 people made a purchase with the company. But, by the next month, that number drops to 4, and then 2 
and then 0, and then 1. This means the Semptember cohort went from 32 customers in month zero, to 4 repeat 
customers in October (month one), to 2 customers in month three, then 0 customers in month four, and finally making a 
gain of 1 customer in month 5.

# Retention Rates

Another pivot table that directly builds off the previous one. However, instead of showing numbers, it shows a specific 
percentage of the customers who stayed from the starting cohort size. Notice at the top in the column headers it shows 1, 
2, 3, and 4, but doesn't begin with 0. This is because month 0 would be 100% for all cohorts.

![Retention Rate Pivot Table](https://github.com/Luke-H-Anderson/Customer-Conversion_Rate/blob/main/Retention%20Rates.png)

So, using the September cohort as an example, notice how in month one it displays 13%, followed by 6%, 0%, and finally 
3%. This is the number of repeart customers of that cohort, over the intital cohort size.

# Conversion Funnel

Now the conversion funnel, my favorite part. It is simple, but important. Notice there are three columns:
1. Countinuque: the count of each unique customer for that action.
2. Conversion Rate from Pervious Step: the conversion rate of customer from the step before.
3. Conversion Rate from First step: the conversion rate of customers from the very first step.

Let's explore this table together. Notice in the rows where it says "view"? The number next to it, 10453, indicates 
the number of customers who viewed the webpage of the store.

![Conversion Rate Pivot Table](https://github.com/Luke-H-Anderson/Customer-Conversion_Rate/blob/main/Conversion%20Funnel.png)

Then right after that it says, "Shopping Cart" followed by the number 3036. That's the number of customers who added an 
item to their shopping cart. You'll also see that in the next two columns, both say "29%". That's because the previous step 
and the initial step, are the same.

However, in the final row, where it says "Purchase" followed by 1081. That's where the real change begins. We see in the 
second row the percentage shows "36%". That's because the percentage of customers who went from adding an item to their cart 
and making a purchase is 36%. And in the last column, you see it says "10%". This is due to the fact that the percentage of 
customers who viewed the website (the first step), and made a purchase, is 10%.

## Project
If you'd like to view this project and explore my work further. Don't hesitate to click the link below and enjoy the advnture.

[Click here](https://docs.google.com/spreadsheets/d/1lfQbj-Opbrbo8LZzsji6Ks-xXSLSZBndREuYIjDjLAY/edit?usp=sharing)
