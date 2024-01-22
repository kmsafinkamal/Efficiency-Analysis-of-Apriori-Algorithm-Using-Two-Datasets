Apriori algorithm: 
Apriori is a popular algorithm for frequent itemset mining in association rule mining. It scans a 
dataset multiple times to identify frequent itemsets, sets of items that appear together frequently. 
It uses a breadth-first search approach to efficiently generate candidates for frequent itemsets and 
prune infrequent ones. The algorithm employs the "Downward Clouser property," which states 
that any non-frequent itemset's supersets must also be infrequent. By iteratively increasing the 
itemset size, Apriori progressively identifies the most frequent itemsets. These frequent itemsets 
are then used to generate association rules, which highlight meaningful relationships between 
items in the dataset, aiding in market basket analysis and recommendation systems.
Dataset Description: 
Two datasets, namely chess and mushroom, were utilized in the study. The chess dataset 
comprises 3196 transactions, each involving 75 items. In contrast, the mushroom dataset contains 
8124 transactions with 119 items. The sizes of the chess and mushroom datasets are approximately 
335 KB and 558 KB, respectively.
Implementation: 
The Apriori algorithm is implemented in python language. Pycharm software is used for this. The 
configuration of the computer is Intel i7 13th 13700k (5.40 GHz) CPU, 32GB DDR5 (5200MHz) RAM,
RTX 3060ti GDDR6 GPU and Windows 11 pro operating system
