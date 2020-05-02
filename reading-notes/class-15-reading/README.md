# Class 15 Reading: Trees

#### What is a leaf node? Why is it important to be able to find leaf nodes?

A leaf node is a node that has no child nodes below it. It is important to be able
to find the leaf nodes because they tell you the height of the tree and the next
available slot.

#### Describe the differences between pre-order, in-order, and post-order traversal. Why are they called pre, in, and post order?

Pre-order traversal is called pre because you go down the left side reading the
root node BEFORE its left and right children.

In-order traversal is called in order because you read the left node, then the root,
and lastly the right. (If it is sorted this will also read the values in order)

Post-order traversal is called post because you go down the left side reading the
root node AFTER its of the left and right children.

#### What is the height of a fully balanced (each non-leaf node has two children) tree? What is this used for?

The height of a fully balanced tree is the is always Log(n) where n is the number of
nodes in the tree. It can be used to calculate the maximum width of the tree which
is 2^(n-1).

#### How are stacks and queues used in relation to trees?

Stacks and queues are used when you are traversing a tree. You use a call stack to
track the recursive calls made doing a depth first traversal and you use a queue
when you are doing a breadth first traversal.
