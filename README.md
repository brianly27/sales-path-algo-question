Sales Path
A car manufacturer holds their distribution system in the form of a tree
(not necessarily a binary tree) The root is the company itself, and every
node in the tree represents a car distributor that receives cars from the
parent node and ships them to its children NodeList. The leaf nodes are 
car dealerships that sell cars direct to consumers. In addition, every node
holds an interger that is the cost of shipping a car to it.

example:

      0
   /  |   \
  5   3    6
 /  /  \  /  \
4  2  0  1  5
  /  /
 1  10
  \
   1

A path from the factory to a cardealership, which is the path from the root to
a leaf in the tree, is called a Sales Path2D. The cost of a Sales Path is the 
sum of the costs for every node in the path. For example, in the tree above, one 
Sales Path is 0 -> 3 -> 0 -> 10. and its total cost is 13. 

The manufacturer wishes to find the minimal Sales Path cost in its distribution 
tree. Given a node "rootNode" write a function "getCheapestCost" that calculates 
the minimal Sales Path cost in the tree.

