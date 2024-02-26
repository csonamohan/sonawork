
## Will the Customer Accept the Coupon?

As part of this exercise, I thoroughly examined the survey data, which delves into various driving scenarios such as destination, current time, weather, passengers, etc. Subsequently, respondents were asked whether they would accept a coupon if they were the driver. Leveraging this survey data, I conducted an analysis and prepared a concise report that underscores the disparities between customers who accepted the coupons and those who did not.

- Here is the [Survey Data](https://github.com/csonamohan/sonawork/blob/main/data/coupons.csv)
- Here is the [Notebook](https://github.com/csonamohan/sonawork/blob/main/prompt.ipynb)


## Cleaning up the Data

The survey data provided encompasses both user attributes and contextual attributes, providing valuable insights into user preferences. However, certain contextual attributes contain null values, necessitating data cleaning to replace these null values with appropriate alternatives. Additionally, some attribute values were excessively lengthy or complex, requiring cleaning procedures to streamline the data processing.

## Exploring the data

A detailed look at the user attributes of the coupon takers some interesting facts - 
* Drivers under the age of 40 mostly take coups
* Most are single or with partner (married or not).
* Their income is mostly under $62.5K
* They have some college education with graduation complete or not.
* They can be of either sex
* Users typically take coupons in sunny weather - during the second half of the day when they either going home or no place urgent.

![Alt text](images\image-1.png)

I took a deeper into the coupon usage / acceptance data to narrow my study. 

![Alt text](images\image.png)

Most popular coupons by Age Group along with their Acceptance Rate

| Age Group    | Coupon Type | Acceptance Rate |
| -------- | ------- | ------- |
| Under 25  | Restaurant(<20)    |74.0 |
| Under 30 | Carry out & Take away     |73.2|
| Under 40     | Carry out & Take away  |72.2|
| Under 50     | Restaurant(<20)  |72.7|
| 50plus    | Carry out & Take away  |77.5|



## Findings

From what is seen here, it is clear that coupons most utilized for Carry out & Takeaway and cheaper restaurants. We can investigate the coupon acceptance rate of Carry out & Takeaway group further. We will look at income of people who utilize this category of coupons, their marital status and when do they most often use this coupon. We will also explore the effect of children on this decision.

![Alt text](images\image-2.png)

### Coupons most utilized for Carry out & Takeaway -
- Overall Acceptance Rate: 0.74
- Most people who use this category of coupons do it 3+ times.
- Widowed, 50+ year olds 
- Chances of takeouts are higher when they have children 
- They are from the lower income group 
- They use mostly these coupons when their destination is home