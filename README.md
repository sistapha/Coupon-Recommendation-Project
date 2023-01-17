
# Coupon Recommendation System: Exploratory Data Analysis

### Will a Customer Accept the Coupon?

**Context**

Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near where you are driving. Would you accept that coupon and take a short detour to the restaraunt?

**Overview**

The goal of this project is to distinguish between customers who accepted a driving coupon versus those that did not.

**Data**

This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \\$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\\$20 - \\$50). 

## FAQ

#### Summary of Findings

**Destination:** Customers going to 'No Urgent Place' (63%) have a higher coupon accpetance rate than other customers.

**Passengers:** Customers who go out with 'Friends' have the highest coupon acceptance rate (67.3%).

**Weather:** Customers who go out in 'Sunny' weather have the highest coupon acceptance rate (59.3%).

**Time:** A majority of the respondents are driving at 6PM (presuambly after-work) or 7AM (presumably (driving to work). However, Acceptance rate of coupons is the highest for customers driving at 2PM (66%) OR 10AM (60%).

**Establishment Type:** Acceptance rate of coupons is the highest for carry out & take away (73.3%) AND cheaper restaurants (< USD20) (70.8%).

**Gender:** Males have a slightly higher acceptance rate (58.9%) than Females (54.6%).

**Age:** Respondents between ages 21-31 account for ~57% of total responses AND have a coupon acceptance rate of 58.2%.

**Marital Status:** Respondents who are either 'Single' (60%) OR are 'unmarried with a partner' (56.1%) have the highest coupon acceptance rates.

**Income:** Respondents with income in the range 'less than 12500' (59.2%) AND '25000-37499' (59.3%) have the highest coupon acceptance rate. Interestingly, respondents in the higher income brackets '100000 or More' also had high coupon acceptance rates (57.8%).

**Bar Coupons:** Respondents who visited the bar between '1-3' (62.1%) times AND '4-8' (63.5%) times had high coupon acceptance rates. Respondents who visited the bar between '4-8' (78.0%) times AND 'gt8' (73.5%) times had high BAR coupon acceptance rates.

**Coffee House Coupons:** Respondents who visited the coffee house between '1-3' (65.3%) times AND '4-8' (63.2%) times had high coupon acceptance rates. Respondents who visited the coffee house between '4-8' (68.6%) times AND 'gt8' (65.8%) times had high coffee house coupon acceptance rates.

**Cheap Restaurant (Under USD20) Coupons:** Respondents who visited a 'Restaurant Less Than 20' 'more than 8' (60.7%), '4-8' (58.4%) times AND '1-3' (56.2%) times had high coupon acceptance rates. Respondents who visited a 'Restaurant Less Than 20' 'more than 8' (76.0%), '4-8' (71.9%) times AND '1-3' (70.7%) times had high Restaurant Less Than 20 coupon acceptance rates.

**Mid-Priced Restaurant (Between USD20 and USD50) Coupons:** Respondents who visited a 'Restaurant20to50' '1-3' (59.4%) times had high coupon acceptance rates. Respondents who visited a 'Restaurant20to50' 'gt8' (68.75%) times AND '4-8' times (62.6%) had high Restaurant20to50 coupon acceptance rates.


## Documentation

[Coupon Recommendation System Exploratory Data Analysis Code](/Coupon_Code_Acceptance_EDA.ipynb)
