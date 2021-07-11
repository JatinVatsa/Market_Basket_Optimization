# Market_Basket_Optimization
In this project we can find the Market Basket Analysis where sales data of supermarkets are mined to find hidden buying patterns of customers. Some buying habits are quite obvious like people who bought milk are very likely to buy bread as well.

But some patterns came as a surprise for e.g. beers and diapers were frequently purchased items because Dads who used to go to the market for purchasing diapers also used to buy beer! 



Association rule mining is a data mining technique to find hidden associations, frequent itemset patterns, and correlations within data. It is essentially a rule-based machine learning technique that generates rules by finding hidden patterns within the data.Such hidden insights have helped supermarkets and stores to design their shelves accordingly. They place frequently purchased items within close proximity to prompt customers to purchase them together.
Alternatively, if the association is quite strong between the items then they can be placed on opposite ends of the store to prompt customers to walk all the way across with the hope they put more items in their basket on their way.

Now the online version of “customers who bought this item also bought” can be seen on e-commerce websites like Amazon, but instead of association rules they use more sophisticated recommendation techniques like collaborative filtering that are based on personalization.





Steps for Apriori Algorithm

Below are the steps for the apriori algorithm:

Step-1: Determine the support of itemsets in the transactional database, and select the minimum support and confidence.

Step-2: Take all supports in the transaction with higher support value than the minimum or selected support value.

Step-3: Find all the rules of these subsets that have higher confidence value than the threshold or minimum confidence.

Step-4: Sort the rules as the decreasing order of lift.




Output for above code
![image](https://user-images.githubusercontent.com/85051683/125205763-7d9d3980-e2a1-11eb-8515-df941e165a63.png)

for better understanding of code


![image](https://user-images.githubusercontent.com/85051683/125205801-a6bdca00-e2a1-11eb-81dd-f419e9a38545.png)


From the above output, we can analyze each rule. The first rules, which is Light cream → chicken, states that the light cream and chicken are bought frequently by most of the customers. The support for this rule is 0.0045, and the confidence is 29%. Hence, if a customer buys light cream, it is 29% chances that he also buys chicken, and it is .0045 times appeared in the transactions. 
