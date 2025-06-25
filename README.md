
# Al Bundy's Sales Analysis - Confidence Interval of Shoe Sales using Inferential Statistics and MS Excel
## Project Objective
Using MS Excel and Inferential Statistics, the objective is to compare the confidence interval (CI) of Al Bundy's shoe sales in the United States in the year 2014-2016 with 95% confidence level. Also, to compare the shop performance of US1 and US2. This is for the inventory of  the shoes to know what sizes are to order more and what are the order less to avoid random ordering of shoe stocks.

## Data used
- <a href = "https://github.com/pagonzales/Inferential_Statistics_Al-Bundy_Shoe_Sales_Analysis/blob/main/AI%20Bundy%20Dataset.xlsx">Dataset</a>
## Questions
- With 95% confidence level,
  - What are the confidence interval of shoe sales in terms of its sizes in the United States. Compare the following years (Calculate in terms of Male and Female):
    - 2014-2015
    - 2015-2016
  - What is the number of shoes that are likely to be sold in the period 
    - 2014-2015
    - 2015-2016
  - Compare the result using t-statistic
  - By how much does the one shop outperforms the other in terms of sales (Use US1 shop and US2 shop)

## Process
- Make a distribution table that is based on categories such as,
  - Shoe size
  - Country
  - Gender
- Given that Al Bundy is operating for more than 30 years, we can apply the Central Limit Theorem
- Then, we can assume normality and create a distribution frequency table of United States sales in terms of shoe size (as rows) and month (as columns)
- After this, we can now proceed to calculate the mean, standard error, margin of error, and get the confidence interval. Also, rounding off the pair of shoes is important (do this for each year bracket like in the Questions section).
- Repeat the creation of distribution frequency table for comparing the shop performance of US1 and US2 in terms of sales then we use the pooled variance to further analyze the CI.

## Image
- For the CI of number of pairs of shoes in the year 2014-2015 (using t-statistic)
  - For male
    ![image](https://github.com/user-attachments/assets/a2801dd9-ff9e-4481-b89e-9ecc9b460259)
  - For female
    ![image](https://github.com/user-attachments/assets/9c7cae4d-0b6e-4cec-9f9b-fb1c5949d695)

- For the CI of number of pairs of shoes in the year 2015-2016 (using t-statistic)
  - For male
    ![image](https://github.com/user-attachments/assets/8cd2ec94-4a1b-42d1-98f1-ec624c96a9df)
  - For female
    ![image](https://github.com/user-attachments/assets/aacfc979-4b33-4566-ad35-6ba442d196f3)

- For Shoe Sales comparison between US1 shop and US2 shop
  - For male
    ![image](https://github.com/user-attachments/assets/0f9f4d41-5dac-472e-a87d-ecc93b41c2cd)
  - For female
    ![image](https://github.com/user-attachments/assets/214c759d-e016-45a3-97a2-88a193500fc9)



## Project insights
 Using the data set of Al Bundy's shoe sales, we use inferential statistics with 95% confidence interval and found out that, for United states;
- For male;
  - In the year 2014-2015 period (using t-statistic) with 95% confidence level, the most ordered shoe sizes are from US 8.5-11 (using the max value in CI range) and 0 order for size 16.
  - In the year 2015-2016 period (using t-statistic) with 95% confidence level, the most ordered shoe sizes are from US 8-11.5 (using the max value in CI range) and 0 order for size 16.
- For female;
  - In the year 2014-2015 period (using t-statistic) with 95% confidence level, the most ordered shoe sizes are from US 7-9.5 (using the max value in CI range) and 0 order starting size 13 to size 16.
  - In the year 2015-2016 period (using t-statistic) with 95% confidence level, the most ordered shoe sizes are from US 6.5-9.5 (using the max value in CI range) and 0 order starting size 13 to size 16.
In comparison of US1 shop and US2 shop in terms of sales, with 95% Confidence level we can see that all CI starts with negative and finish with positive values (with the exception of zero values).
With this, we cannot conclude that one shop sells more shoes than the other for any size. This also means that the CI is not in favor for any specific shop selling more than the other. This tells us
that US1 sells more, while for others - vice versa. But with the methodology used and level of confidence we cannot identify which shop sells more. They are identical.

## Final Conclusion
For the year 2014-2015 and 2015-2016, with 95% confidence level, we can order a number of pair shoes indicated in the images above (in the max value of CI) for the stocks to have a smooth in and out flow per sizes or using the max values in both periods and CI, the shop can order the following for flow of stocks with the assumption that the shop should not run out of stocks in heavy orders.
 - For male
  - For size 6 - order 3 pairs
  - For size 6.5 - order 2 pairs
  - For size 7 - order 2 pairs
  - For size 7.5 - order 3 pairs
  - For size 8 - order 6 pairs
  - For size 8.5 - order 9 pairs
  - For size 9 - order 17 pairs
  - For size 9.5 - order 27 pairs
  - For size 10 - order 20 pairs
  - For size 10.5 - order 16 pairs
  - For size 11 - order 8 pairs
  - For size 11.5 - order 6 pairs
  - For size 12 - order 4 pairs
  - For size 13 - order 2 pairs
  - For size 14 - order 3 pairs
  - For size 15 - order 1 pair
  - For size 6.5 - order 0 pair
- For female
  - For size 6 - order 2 pairs
  - For size 6.5 - order 5 pairs
  - For size 7 - order 5 pairs
  - For size 7.5 - order 13 pairs
  - For size 8 - order 22 pairs
  - For size 8.5 - order 15 pairs
  - For size 9 - order 15 pairs
  - For size 9.5 - order 6 pairs
  - For size 10 - order 3 pairs
  - For size 10.5 - order 4 pairs
  - For size 11 - order 1 pairs
  - For size 11.5 - order 2 pairs
  - For size 12 - order 2 pairs
  - For size 13 - order 0 pairs
  - For size 14 - order 0 pairs
  - For size 15 - order 0 pair
  - For size 6.5 - order 0 pair

Also, for the shops US1 and US2, we cannot tell which shop sells more than the other. The CI simply shows that these two shops are so balanced in terms of sales that they can share the same warehouse 
or exchange pair of shoes to achieve better results.
