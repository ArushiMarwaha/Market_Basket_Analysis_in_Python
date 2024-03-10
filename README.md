# Market Basket Analysis in Python using Apriori Algorithm

## Description
When you go to a supermarket, you've probably noticed how things like baby diapers and wipes, bread and butter, pizza ingredients, beer, and chips are often placed together to encourage sales. Market basket analysis is all about studying the connections between products that customers buy together. It's a useful tool for retail stores to promote related products and for online shops to recommend items based on what customers usually buy together. The go-to methods for this kind of analysis are Apriori and FP growth, two popular machine learning algorithms. They help make sense of customer shopping patterns and preferences.

### Apriori Algorithm
Apriori algorithm is given by R. Agrawal and R. Srikant in 1994 for finding frequent itemsets in a dataset for boolean association rule. Name of the algorithm is Apriori because it uses prior knowledge of frequent itemset properties. We apply an iterative approach or level-wise search where k-frequent itemsets are used to find k+1 itemsets.

To improve the efficiency of level-wise generation of frequent itemsets, an important property is used called Apriori property which helps by reducing the search space.

**Apriori Property** – All non-empty subsets of frequent itemset must be frequent. The key concept of Apriori algorithm is its anti-monotonicity of support measure. Apriori assumes that
- All subsets of a frequent itemset must be frequent (Apriori property). If an itemset is infrequent, all its supersets will be infrequent.

*Source: GeeksforGeeks*
