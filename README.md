# Coupon-Acceptance-Rate-by-Drivers-PA_5-
Dataset investigation and analysis - will a driver accept a coupon sent while driving? The data was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. 

The Jupyter notebook encompas a brief report that highlights the differences between customers who did and did not accept the coupons.  

User attributes:
Gender: male, female
Age: below 21, 21 to 25, 26 to 30, etc.
Marital Status: single, married partner, unmarried partner, or widowed
Number of children: 0, 1, or more than 1
Education: high school, bachelors degree, associates degree, or graduate degree
Occupation: architecture & engineering, business & financial, etc.
Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc.
Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she eats at a restaurant with average expense less than $20 per person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

Contextual attributes:
Driving destination: home, work, or no urgent destination
Location of user, coupon and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with time of driving. The user can see whether the venue is in the same direction as the destination.
Weather: sunny, rainy, or snowy
Temperature: 30F, 55F, or 80F
Time: 10AM, 2PM, or 6PM
Passenger: alone, partner, kid(s), or friend(s)
Coupon attributes
time before it expires: 2 hours or one day.

Contents of the Jupyter Notebook:

1. Read in the coupons.csv file.

2. Investigate the dataset for missing or problematic data. 
   The original dataset has 12,684 entrie, 25 feature columns, and 1 target classification column: Y (Y: 1 - accept, 0 - do not accept coupon).
   
3. Decide what to do about your missing data -- drop, replace, other.

4. What proportion of the total observations chose to accept the coupon?

 Visualization of Target column

 Histogram of Temperature Col.

 Investigating the Bar Coupons among Bar goers:
      4.3 Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.
      4.4 Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is       there a difference?
      4.5 Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.

6. Compare the acceptance rates between drivers 

7. Based on these observations, what do you hypothesize about drivers who accepted the bar coupons?

- Independent Investigation
   Among Age, Occupation, Marital Status Columns. Including conclusions per each.








