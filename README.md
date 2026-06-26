# B141-Data-Mining
B141 Data Mining  Market Basket Analysis (The Bread Basket)

My individual project for B141. I used Market Basket Analysis with the Apriori
algorithm to find which bakery products customers usually buy together.

Dataset

The Bread Basket – real bakery transactions (~9,500 transactions, 94 items).
Source: https://www.kaggle.com/datasets/mittalvasu95/the-bread-basket

I didn't upload the raw CSV here. Download bread basket.csv from the link above to run it.

What I did


Cleaned the data (fixed item names, removed "NONE", dropped duplicate item rows)
Some quick EDA (
Implemented Apriori from the lecture pseudo-code to get frequent itemsets
Generated association rules and scored them with confidence and lift
Compared weekend vs weekday patterns
