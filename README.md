
In this project we analyse a simple dataset from the real estate industry. 
We perform some exploratory data analysis, perform hypothesis testing and create a simple linear regression to understand the relationship between average rooms and the median home value.
1. Data analysis
   Here we read and explore the data using summary statistics and descriptive statistics. We look for missing variables, as well as compute the mean, mode and median of our numerical variables. We also compute a correlation matrix to find the variable with the highest correlation to price.
2. Data visualization
   We limit the visualization portion of the project to creating a histogram of the distribution of median home values.
  ![Rplot](https://github.com/ElitsaKal/Housing-Data-Analysis-in-R/assets/162779608/8ed2e958-3ccf-4ea4-9173-2c723fb56acd)
3. Hypothesis testing
  For this test we wish to understand the effect of crime rates on median home values. We perform a two-sample independent T-test to test our hypothesis:
Null Hypothesis (H0​): The median home values are the same for areas with high and low crime rates.
Alternative Hypothesis (H1​): The median home values differ for areas with high crime rates compared to areas with low crime rates.
4. Linear regression
  Finally, we create a regression scatter plot using ggplot2 to visualize the relationship between the number of average rooms in a home and the median home value.
![Rplot01](https://github.com/ElitsaKal/Housing-Data-Analysis-in-R/assets/162779608/33665862-fd31-4a7e-99dd-0665a88df3b6)
