# FP-Growth-Algorithm
This algorithm is an improvement to the Apriori method. A frequent pattern is generated without the need for candidate generation. FP growth algorithm represents the database in the form of a tree called a frequent pattern tree or FP tree.

This tree structure will maintain the association between the itemsets. The database is fragmented using one frequent item. This fragmented part is called “pattern fragment”. The itemsets of these fragmented patterns are analyzed. Thus with this method, the search for frequent itemsets is reduced comparatively.

In here we have apply FP growth algorithm on cosmetic data set which was extracted from an online store.
https://www.kaggle.com/mkechinov/ecommerce-events-history-in-cosmetics-shop

We have selected only the purchase event_type and try to find association rules between user purchase brands.
Applied minSup = 0.01 and minCon = 0.01

Result Interpretation 😊
In most of the rules predicted item is runail brand or irisk brand. It conclude that customers always trend to buy products with these brands.
