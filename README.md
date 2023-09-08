# Walmart-EDA
![image](https://github.com/AaryanPurohit/Walmart-EDA/assets/112640418/25ab9692-1694-4ce8-8f82-c42774cf9df8)

## Overview

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

## Understanding the Dataset
The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:

1. **User_ID**: User ID
2. **Product_ID**: Product ID
3. **Gender**: Sex of User
4. **Age**: Age in bins
5. **Occupation**: Occupation(Masked)
6. **City_Category**: Category of the City (A,B,C)
7. **StayInCurrentCityYears**: Number of years stay in current city
8. **Marital_Status**: Marital Status
9. **ProductCategory**: Product Category (Masked)
10. **Purchase**: Purchase Amount

## Inferences
1. 80% of the users are between the age 18-50 (40%: 26-35, 18%: 18-25, 20%: 36-45)
2. 75% of the users are Male and 25% are Female. Males clearly purchase more than females.
3. 59% Single, 41% Married
4. 35% Staying in the city from 1 year, 18% from 2 years, 17% from 3 years
5. The majority of our customers come from city category B but customers come from City category C spent more as mean is 9719.
6. The majority of users come from City Category C, but more people from City Category B tend to purchase, which suggests the same users visit the mall multiple times in City Category B.
7. Majority of Customers purchase within the 5,000 - 20,000 range.
8. Most mall customers are between the ages of 26 and 35.60% of purchases are made by people between the ages of 26 and 45
9. City Category B accounts for 42%, City Category C 31%, and City Category A represents 27% of all customer purchases.Purchases are high in city category C
10. Most mall customers are between the ages of 26 and 35. City category C has more customers between the ages of 18 and 45.
11. In City Category C, there are slightly more female customers.
12. Product 5 and 8 is common among females.

## Recommendations
1. Men spent more money than women, So company should focus on retaining the male customers and getting more male customers.
2. Product_Category - 1, 5, 8, & 11 have highest purchasing frequency. it means these are the products in these categories are liked more by customers. Company can focus on * selling more of these products or selling more of the products which are purchased less.
3. Unmarried customers spend more money than married customers, So company should focus on acquisition of Unmarried customers.
4. Customers in the age 18-45 spend more money than the others, So company should focus on acquisition of customers who are in the age 18-45.
5. Male customers living in City_Category C spend more money than other male customers living in B or C, Selling more products in the City_Category C will help the company increase the revenue.
6. In light of the fact that females spend less than males on average, management needs to focus on their specific needs differently. Adding some additional offers for women can increase their spending on Black Friday.
7. Management should come-up with some games in the mall to attract more younger generation will can help them to increase the sale.
8. The management should have some offers on kids (0-17 years) in order to increase sales.
9. In order to attract more young shoppers, they can offer some games for the younger generation.

Explore this repository to uncover fascinating details about Walmart's data!!!
