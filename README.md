# target_guided.encoding
-------------------------------------------------Readme------------------------------------------------------------
Target guided ordinal encoding is a feature encoding technique in machine learning where categorical variables are
assigned numerical values based on their relationship with the target variable.
Steps:
Group by Category:

A: [1, 0]
B: [2, 1]
C: [3, 2]
Calculate Mean Target:

A: (1 + 0)/2 = 0.5
B: (2 + 1)/2 = 1.5
C: (3 + 2)/2 = 2.5
Assign Ordinal Ranks:

A: 1 (lowest mean)
B: 2
C: 3 (highest mean)
Replace Categories:

Encoded Dataset:
