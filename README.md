# C4.5-ALGORITHM

*Another version of the ID3 algorithm.
*Uses entropy.

# What is Entropy in decision tree?

Entropy : A decision tree is built top-down from a root node and involves partitioning the data into subsets that contain instances with similar values (homogeneous). ID3 algorithm uses entropy to calculate the homogeneity of a sample.

# What is Information Gain in decision tree?

Information Gain: The information gain is based on the decrease in entropy after a data-set is split on an attribute. Constructing a decision tree is all about finding attribute that returns the highest information gain (i.e., the most homogeneous branches).

Entropy = > Info(D) 

A's knowledge => InfoA(D)

Information Gain => Gain(A)= Info(D)-InfoA(D)

A is : target values
D is : target variable

