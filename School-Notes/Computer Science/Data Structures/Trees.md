A binary tree can be traversed in three ways: 
- Pre-order: Visit the root, then traverse the left sub-tree, then the right sub-tree.
- In-order: Traverse the left sub-tree, then visit the root, then traverse the right sub-tree.
- Post-order: traverse the left sub-tree, then traverse the right sub-tree, then visit the root.

A binary search tree holds items in such a way that the tree can be searched quickly and easily for a particular item. To make a binary search tree nodes are added in the order given, with the first item at the root. Starting at the root each time, if the next item is less than the root, it is added to the left of the root, otherwise, to the right. Apply the same rule at the root of each sub-tree. A balanced tree is one where the nodes are distributed in such a way that the height is kept to a minimum.