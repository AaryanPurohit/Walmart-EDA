# Walmart-EDA
![image](https://github.com/AaryanPurohit/Walmart-EDA/assets/112640418/25ab9692-1694-4ce8-8f82-c42774cf9df8)

## Overview
Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

**In this case study, I delved into a massive dataset comprising a staggering 0.54 million rows to unlock invaluable insights into customer shopping behavior at the retail giant, Walmart. This endeavor involved a combination of exploratory data analysis (EDA), statistical analysis using the Central Limit Theorem, and the powerful Bootstrapping technique.**

## Exploratory Data Analysis (EDA)
🔍 Exploratory Data Analysis (EDA) was our first port of call. I embarked on a comprehensive adventure, dissecting the dataset through univariate, bivariate, and multivariate analyses. The toolkit included histograms, box plots, pair plots, correlation plots, KDE plots, and more. The goal? To unearth patterns, trends, and hidden gems within this vast sea of data. The revelations were nothing short of captivating. 💎📊

## Central Limit Theorem and Bootstrapping
📈 The **Central Limit Theorem** became the backbone of our analysis. Leveraging its power, I employed the **Bootstrapping technique** – a resampling marvel – to gain deeper insights into the dataset.

Here's how Bootstrapping elevated our analysis:
**Comparison of Spending Habits**: I resampled purchase values for both males and females, enabling a detailed comparison of their spending habits. 👫
**Analyzing Marital Status**: Resampling purchase values based on marital status allowed for an in-depth examination of order values for married and unmarried customers. 💍
**Understanding Age Groups**: By resampling purchase values according to age groups, I could precisely assess spending patterns across different demographics. 👴👵

This approach yielded multiple simulated datasets, each brimming with valuable insights and a refined understanding of Walmart's diverse customer base. 📊💡

## Statistical Analysis with Confidence Intervals
🔬 The journey continued with **statistical analysis** conducted at various **confidence intervals** (90%, 95%, and even 99%). These confidence intervals emerged as potent tools, offering a glimpse into the potential range of values for key metrics. Decision-makers can now rely on more accurate information for strategic choices. 📊🔍

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

## Dive into the Insights
### Inferences
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

### Recommendations
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
