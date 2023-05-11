# Online_Retail
Online purchase analysis for a retail store in the United Kingdom involves finding purchasing
behaviors of customers using association rule mining to identify actionable insights between
products. It employs online retail data to discover frequent itemsets in transactions and
identifies association rules between these items. The discovery of these actionable rules enhance the sales of itemsets
in the analyzed rules and improve marketing strategies for the retail business. The model performance is measured
by confidence and lift. Exploratory data analysis and preparation techniques were applied to the dataset prior to creating a subset of the data with the selected 
region and a basket of items per customer (item_list). 

The item_list was transformed using the hot encode function to fit the model. The minimum support parameter is set to 0.02 to identify more rules, the lift measure represents the strength of associations, and interesting association rules have a lift larger than 1. Thus the set parameter identified 182
rules. 

# Results and Analysis
![image](https://github.com/m33nm/Online_Retail/assets/54365936/98c8a8a8-f097-471b-bb56-19238ef75547)
Figure 1: Graphical overview of the identified association rules

Figure 1 shows that there are engaging and actionable rules with high confidence and lift value in the dataset. Thus, the specific areas with these values were explored.

![image](https://github.com/m33nm/Online_Retail/assets/54365936/2752d0b0-902f-4c7b-8126-b22d363a8e96)
Figure 2: Identified actionable rules

Using the red highlighted association rule in Figure 2, it shows that:
[Pink Regency Teacup & Saucer (X) --> Green Regency Teacup & Saucer (Y)]
has a confidence value of 0.82 and a lift of 16, which means there is an 82% probability that a
customer would purchase Y, given that X is present. The lift means that X and Y are positively
correlated, indicating a solid association rule (greater lift values indicate stronger association).

Further analysis of the actionable rules shows that customers in the UK like to purchase
tea plates of different colors. I assessed the number of purchases for each color of the tea
plates. The results showed that the rose-colored sets are in higher demand than the
green, followed by the pink-colored set. This result can help producers/retailers ensure
that the rose-colored tea plates are always in supply.

# Conclusion
Association rule mining discovered the frequent itemsets of an online retail store in United Kingdom. The results
would help the retailer/manager know the relationship between items/services they provide and
use this data to adjust their structure, cross-selling, and promotions based on statistics. The
discovery of these actionable rules would help the business develop/improve its marketing
strategies.
