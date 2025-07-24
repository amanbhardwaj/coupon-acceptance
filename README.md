# coupon-acceptance
### Project
This project aims to analyze data and draw insights into the factors that determine a driver's accepance of a coupon delivered to them under various circumstances. The objective is exploratory statistical data analysis and visualization of user and contextual attributes that impact acceptance of coupons people receive while driving. How would you determine whether a driver is likely to accept a coupon or not?

### Data
The data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes user attributes like gender, age, marital status, children, occupation, income, visiting frequency to restaurants, bars, takeaways, coffee houses as well as different driving scenarios like driving destination, current time, weather, temperature, passenger and then ask people whether they will accept the coupon if they are the driver. Possible answers to choose: 1. Right away, 2. Later before the coupon expires, 3. No, I do not want the coupon (1 and 2 are acceptance of coupon).

### Coupon Groups: 
- Less expensive restaurants (under $20)
- Coffee House
- Carry out & Take away
- Bar
- More expensive restaurant($20 - $50)

### Coupon Groups analyzed: 
- Bar
- More expensive restaurant($20 - $50)


### A - Bar Coupons

Based on the observations, drivers with high acceptance rate of the bar coupons are the onces:
- who go to a bar more than 3 times a month (0.769)
- who go to a bar more than once a month (0.688)
- who go to a bar more than once a month and are over the age of 25 (0.695)
- who go to a bar more than once a month and had passengers that were not a kid (0.713)
- who go to a bar more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry (0.713)
- who go to a bar more than once a month and had passengers that were not a kid, and were not widowed (0.713)
- who go to a bar more than once a month and are under the age of 30 (0.722)

**NOTE:** Upon closer look, all the drivers who go to a bar more than once a month and had passengers that were not a kid, they all have occupations other than farming, fishing, or forestry and are not widowed.

Therefore based on my hypothesis the folloing drivers are more likely to accept Bar coupons:
- who go to a bar more than 3 times a month.
- who go to a bar more than once a month.
- who go to a bar more than once a month and are between the age of 25 and 30.
- who go to a bar more than once a month and had passengers that were not a kid.

### B - Restaurant($20 - $50) Coupons

Hypothesis based on observations

Characteristics and contextual attributes of people who are twice as likely to accept a coupon from more expensive restaurants ($20 - $50) are:
People who go to a expensive restaurant 1-3 times a month, are unmarried partners, while driving with a partner in a sunny weather around 10 AM 
