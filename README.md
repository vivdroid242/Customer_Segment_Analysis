# Customer_Segment_Analysis

## Business Problem:
**Aerofit** specializes in selling high-quality treadmills directly to individual customers for home use. 
The company aims to identify the target audience for each type of treadmill it offers in order to provide better recommendations to new customers. Apart from that, they want to determine whether they should focus on selling a single model or continue offering multiple models.

## Product Portfolio 
- The KP281 is a treadmill for beginners that sells for $1,500.
- The KP481 is for mid-level runners and sells for $1,750.
- The KP781 treadmill is for professionals, it has advanced features and it sells for $2,500.

## Data Dictionary
- Product - Treadmill model (e.g., "KP281").
- Age - Age of the individual (in years). 
- Gender - Gender of the individual (e.g., "Male", "Female").
- Education - Number of years of formal education completed by the individual.
- MaritalStatus - Marital status of the individual (e.g., "Single", "Partnered").
- Usage - Frequency of treadmill usage per week (1 = low, 5 = high).
- Fitness - Self-assessed fitness level (1 = low, 5 = high).
- Income - Annual income of the individual (in USD).
- Miles - Estimated number of miles run per week on the treadmill.
- Price - Price of the treadmill purchased (in USD).

## Insights

![image](https://github.com/user-attachments/assets/03dd4acc-9ba1-466e-bb14-7643c3a2fca6)
- KP281 is the most frequent and best-selling product.
- In Gender, there are more Males who are using treadmills than Females.
- Treadmills are more likely to be purchased by partnered people

![image](https://github.com/user-attachments/assets/e218d9bd-64b9-405e-adfa-ac4250887d21)
- The majority of customers are aged between 20-30.
- Customers with 14-16 years of education buy a major chunk of treadmills
- The majority of the customers expect to use the treadmills 3-4 times a week
- Customers with fitness lev 3 buy a major chunk of treadmills
- Majority of Customers fall within the 40,000-60,000 income range

![image](https://github.com/user-attachments/assets/cbcb894d-ffe6-42fc-a714-4e9acbf245ab)
- Customers purchasing products KP281 & KP481 are having the same Age median value. Customers whose age lies between 25-30, are more likely to buy the KP781 product
- Customers whose Education is >=16, have more chances to purchase the KP781 product. While the customers with Education less than 16 have equal chances of purchasing KP281 or KP481.
- Customers who are planning to use the treadmill more than 4 times a week, are more likely to purchase the KP781 product. While the other customers are likely to purchase KP281 or KP481.
- Customer having fitness levels >= 3 have a higher chance purchasing the KP781 product.
- The higher the Income of the customer (Income >= $60000), the higher the chances of the customer purchasing the KP781 product.
- If the customer expects to walk/run greater than 120 Miles per week, it is more likely that the customer will buy the KP781 product.

![image](https://github.com/user-attachments/assets/0c713d0f-5938-4a4b-945b-c870209ba93c)
- **KP281:**
The model has generated the highest revenue, with customers in their 20s showing a preference for it. It is equally popular among males and females. Customers who have completed 14 or 16 years of education and are in a relationship tend to favor this model. They typically use it 3-4 times a week, have a fitness level of 3 out of 5, and earn between $35,000-$60,000.
- **KP481:**
The model has generated the 2nd highest revenue, the consumer insights are identical to KP281. The only difference is that they typically use it 2-3 times a week.
- **KP781:**
The model has generated the 3rd highest revenue. It is majorly popular among males. Customers who have completed 16 or 18 years of education and are in a relationship tend to favor this model. They typically use it 4-5 times a week, have a fitness level of 5 out of 5, and earn > $60,000.

![image](https://github.com/user-attachments/assets/1e112e3f-611d-43f8-b8ad-a73bbc740002)
- (Miles & Fitness) and (Miles & Usage) attributes are highly correlated, which means if a customer's fitness level is high they use more treadmills.
- Income and Education shows a strong correlation. High-income and highly educated people prefer the KP781 treadmill which is having advanced features.
- There is no correlation between (Usage & Age) or (Fitness & Age) attributes, which mean Age should not be a barrier to using treadmills or specific model of treadmills.

# SUMMARY

### Target Market:
The majority of treadmill customers, who are typically aged between 20-30 and have 14-16 years of education, expect to use the treadmills 3-4 times a week, with a fitness level of 3, and fall within the income range of $35,000-$60,000; they are more likely to be male and partnered.

### KP781 Customer Profile:
- Age: More likely to be in the age range of 25-30.
- Gender: More popular among males.
- Education: Typically completed 16 or 18 years of education.
- Relationship Status: Usually in a relationship.
- Usage: Prefer to use it 4-5 times a week.
- Fitness Level: Have a fitness level of 5 out of 5.
- Income: > $60,000

### KP481 Customer Profile:
- Age: Typically in their 20s.
- Gender: Equally popular among males and females.
- Education: Typically completed 14 or 16 years of education.
- Relationship Status: Usually in a relationship.
- Usage: Prefer to use it 2-3 times a week.
- Fitness Level: Have a fitness level of 3 out of 5.
- Income: $35,000-$60,000.

### KP281 Customer Profile:
- Age: Primarily in their 20s.
- Gender: Equally popular among males and females.
- Education: Typically completed 14 or 16 years of education.
- Relationship Status: Usually in a relationship.
- Usage: Prefer to use it 3-4 times a week.
- Fitness Level: Have a fitness level of 3 out of 5.
- Income: $35,000-$60,000.
