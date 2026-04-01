# Apriori_Based_Market_Analysis

Finds frequent itemsets and also recommends items in a dataset for boolean association rule. Uses support and confidence factor as antecedent and consequent to solve simple shopping problem.

1. It first transforms transaction data into a one-hot encoded DataFrame for analysis.
2. The Apriori algorithm is applied to find frequent itemsets with high support.
3. From these itemsets, association rules are generated using confidence thresholds.
4. A virtual shop is created where users can select items interactively.
5. Each selected item is added to a cart and removed from available inventory.
6. The system checks association rules to find relevant recommendations.
7. Recommendations are based on items frequently bought together (antecedents → consequents).
8. Already selected items are filtered out to avoid duplicate suggestions.
9. The loop continues until the user exits or all items are purchased.
10. Overall, it showcases how Apriori powers real-time product recommendations like in e-commerce platforms.
