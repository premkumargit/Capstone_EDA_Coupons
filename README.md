# Capstone_EDA_Coupons

Jupyter : https://github.com/premkumargit/Capstone_EDA_Coupons/blob/main/prompt.ipynb

## Explore the dataset
# Investigate the dataset for missing or problematic data.

<img src="/images/Missing_values.png" width="350" height="350">

    * Car column has missing 99.15 % of data, and it has 5 different values about what kind of vehicle being used. This column is not very useful for the EDA analysis, could be ignored

    * age is not numeric data type, it has 50plus & below21. This requires conversion if there is any filter based on age group
    * income is not numeric data type. This requires conversion if there is any filter based on age group
     
     
# Decide what to do about your missing data -- drop, replace, other...
  
<img src="/images/Outliers.png" width="350" height="350">

    * There is no Outliers
    * There are 74 duplicated records found, and droped.



## EDA Analysis

# Coupon acceptance distributtion

    A little over 56% of customers accepted the coupon offer (specifically, 56.76%). This inference, with more users accepting coupons than rejecting them

<img src="/images/Coupon_acceptance_distribution.png" width="350" height="350">

# Coupon type

    * Most issued coupon is for Coffee House and least issued coupon is Highend Restaurants
    * Coupons issued for Coffee House and Cheap Restaurants has high acceptance, and they are

<img src="/images/Coupon_Type_Distribution.png" width="350" height="350"> <img src="/images/Coupon_Type_vs_Acceptance.png" width="350" height="350">

# temperature vs Coupon issued

    * Survey distributed more coupons during warmer temperature and less coupons on cold weather
<img src="/images/Issued_Coupon_vs_temperature.png" width="350" height="350">


# Bar Coupon Acceptance
 
    * Only 41% bar coupon has redeemed
    * Driver who visits the bar frequently has the higher acceptance rates(more than 80%)
    * Drivers who are younger (under 30) and also visits bars show higher acceptance rates.
    * Drivers having lower income(< 50k) and visits cheap restaurents show higher acceptance rates.
    * Drivers do not having kids show higher acceptance rates.
    * Bar coupons issued after noon has higher acceptance rate

<img src="/images/Bar_coupons_Proportion.png" width="350" height="350"> <img src="/images/time_vs_Bar_coupon.png" width="350" height="350">
<img src="/images/No_Kids_vs_Bar_Coupon.png" width="350" height="350"> <img src="/images/Young_age_vs_Bar_coupon.png" width="350" height="350">    



     

