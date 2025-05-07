# Capstone_EDA_Coupons

Jupyter : https://github.com/premkumargit/Capstone_EDA_Coupons/blob/main/prompt.ipynb

## Explore the dataset
# Investigate the dataset for missing or problematic data.

![alt text](/images/Missing_values.png?raw=true)

    * Car column has missing 99.15 % of data, and it has 5 different values about what kind of vehicle being used. This column is not very useful for the EDA analysis, could be ignored

    * age is not numeric data type, it has 50plus & below21. This requires conversion if there is any filter based on age group
    * income is not numeric data type. This requires conversion if there is any filter based on age group
     
     
# Decide what to do about your missing data -- drop, replace, other...
  
![alt text](/images/Outliers.png?raw=true)

    * There is no Outliers
    * There are 74 duplicated records found, and droped.



## EDA Analysis

# Coupon acceptance distributtion

    A little over 56% of customers accepted the coupon offer (specifically, 56.76%). This inference, with more users accepting coupons than rejecting them
![alt text](/images/Coupon_acceptance_distribution.png?raw=true)


# Coupon type

    * Most issued coupon is for Coffee House and least issued coupon is Highend Restaurants
    * Coupons issued for Coffee House and Cheap Restaurants has high acceptance, and they are

![alt text](/images/Coupon_Type_Distribution.png?raw=true)
![alt text](/images/Coupon_Type_vs_Acceptance.png?raw=true)

# temperature vs Coupon issued

    * Survey distributed more coupons during warmer temperature and less coupons on cold weather

![alt text](/images/Issued_Coupon_vs_temperature.png?raw=true)

# Bar Coupon Acceptance
 
    * Only 41% bar coupon has redeemed
    * Driver who visits the bar frequently has the higher acceptance rates(more than 80%)
    * Drivers who are younger (under 30) and also visits bars show higher acceptance rates.
    * Drivers having lower income(< 50k) and visits cheap restaurents show higher acceptance rates.
    * Drivers do not having kids show higher acceptance rates.
    * Bar coupons issued after noon has higher acceptance rate
    
![alt text](/images/Bar_coupons_-_Proportion.png=100x100) ![alt text](/images/time_vs_Bar_coupon.png?raw=true)
![alt text](/images/No_Kids_vs_Bar_Coupon.png?raw=true) ![alt text](/images/Young_age_vs_Bar_coupon.png?raw=true)


     

