# Will the Customer Accept the Coupon?
An exploration of coupon acceptance rates

**Jupyter notebook:** https://github.com/cheeseinvert/driving-coupon-eda/blob/main/prompt.ipynb

## What is the problem? 
This project aims to apply exploritory data analysis, visualizations and probability distributions to understand the distinguishing characteristics between customers who accepted coupons presented while driving versus those who did not. Newly aqcuired techniques of statistical summarization are showcased here to present data-driven findings.

## What is the data?
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

- **“Right away”**
- **“Later, before the coupon expires”**
- **“No, I do not want the coupon”**

## What are the findings?
### Single category findings:
Drivers were generally more likely to accept the coupon when looking at the following parameters in isolation:
#### Destination
- not on route to an urgent destination, rather than home or work
#### Passengers
- there were friends in the car, rather than family or no one at all
#### Weather
- outside weather was sunny
#### Temperature
- temperature was warm (80 degrees)
#### Time of Day
- time of day was mid-afternoon (2pm)
#### Coupon Type
- the coupon was for take-out or an inexpensive restaurant (<$20)
#### Expiration
- the coupon had a 1d expiration rather than 2h
#### Gender
- men are slightly more likely than women to accept the coupon
#### Age
- below 21 years old
#### Marital Status
- unmarried and without partner (single)
#### Number of Children
- did not have children
#### Education
- had not yet graduated high school
#### Bar Coupons
- Bar coupon acceptance was highest with drivers who went to the bar between 4 and 8 times a month
#### Cafe and Takeout Coupons
- Coffeehouse and Takeout coupon acceptance was highest with drivers who went to the cafe between 1 and 3 times a month
#### Restaurant Coupons
- Restaurants (<$20 and $20<$50) coupone acceptance was most likely with drivers who frequented those extablishments greater than 8 times a month
#### Time After Coupon Delivery
- Drivers were most likely to use the coupon within the first 5-15min
#### Route Convenience
- Drivers were most likely to use a coupon for a location on the route of their current direction
  
### Multi category findings:
Drivers were generally more likely to accept the coupon when looking at the following parameters in combination:
#### Weather and Time Of Day
- Drivers were curiously most likely to accept a coupon on snowy mornings followed by sunny afternoons
#### Gender and Education
- Male students who had not yet graduated high school were most likely to accept coupons when looking at these parameters in combination
#### Marital Status and Coupon Type
- Widows had a very high acceptance rate for coupons to take out restaurants

## What do I recommend?
Perhaps more data collection to understand why mornings on a snowy day are likely to yeild higher coupon acceptance rates. Additionally coupons should be targeted according to route of the driver to make sure they are for places on the way for the particular destination and can be redeemed in a timely and convenient manner. 
