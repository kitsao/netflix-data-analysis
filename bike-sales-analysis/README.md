# Bike Sales Analysis

![Bike Sales Dashboard](https://github.com/kitsao/portfolio-projects/blob/main/bike-sales-analysis/images/bike_sales_dashboard.JPG)


## The Data

The dataset contains bike sales data comprising demographic and equity (matiral status, gender, income ...) information and whether they bought or did not buy a bike. A sneak peek is shown below.

| ID | Marital Status | Gender | Income | Children | Education | Occupation | Home Owner | Cars | Commute Distance | Region | Age | Purchased Bike |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 12496 | M | F | $40,000.00 | 1 | Bachelors | Skilled Manual | Yes | 0 | 0-1 Miles | Europe | 42 | No |
| 24107 | M | M | $30,000.00 | 3 | Partial College | Clerical | Yes | 1 | 0-1 Miles | Europe | 43 | No |
| ... |
| 18484 | S | M | $80,000.00 | 2 | High School | Skilled Manual | No | 2 | 1-2 Miles | Pacific | 50 | Yes |

The data can be accessed [here](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)

In this project, we start by cleaning the data:
 - remove dulicates - useless data that we do not need.
 - replace abbreviations with meaningful phrases such as Married for M, Single for S for Marital Status and Male for M and Female for F for Gender.
 - remove zeros after decimal point for column type currency
 - bucket age into brackets of `Adolescent (<30 years)`, `Middle Age (30 - 54 years)` and `Old (>54 years)` for ease of analysis.


## Insights and Analysis

###### average income per purchase (of a somebody that bought or did not  buy a bike).

![Average Income per Purchase](https://github.com/kitsao/portfolio-projects/blob/main/bike-sales-analysis/images/income_per_purchase.JPG)

  - we can see that females who did not buy averaged 53,400 while those buying averaged 55,774. Generally men averaged more than women in both cases, with bike buyers at 60,123 and non-buyers at 56,208. The more the average disposable income, the lower the likelihood of purchasing a bike.


###### why do they buy bikes? Does commuting distance affect the decision whether or not to buy bikes?

![Customer Commute](https://github.com/kitsao/portfolio-projects/blob/main/bike-sales-analysis/images/customer_commute.JPG)
  - From the chart above, generally, customers with shorter commute distance purchased more bikes than those with longer commute distance. Probably, those with shorter commute distance prefer bikes to other vessels such as cars while those with longer distances prefer other vessels to bikes.


###### what about their ages? Does age have anything to do with the decision to purchase bikes?

![Customer Age Brackets](https://github.com/kitsao/portfolio-projects/blob/main/bike-sales-analysis/images/customer_age_brackets.JPG)

  - under 3 are not buying bikes, 30-54 are buying the most bikes while the old buy fewer bikes. It could be that the middle-aged population purchase bikes to keep fit due to a higher tendency to exercise.


## Recommendations and Future Works

1. Add value to the bikes so that people with high average income can be swayed to purchase. Additionally, marketing campaigns targetting the higher population income will likely see purchases going up.
2. Add new features to the bikes such as electric bikes to convince customers with longer commute to purchase.
3. Offer incentives such as loyalty points and organized events so that the adolescents and old are compelled to buy the bikes.

Future work could include checking the significance of each of and more demographic factors towards the purchase decision.


Thank you for taking the time to look at this starter project! Please [connect](https://www.linkedin.com/in/emmanuel-kitsao-8796a534/) with me and check out my [portfolio](https://kitsao.github.io)!

