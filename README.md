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

