#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [LinkedLists](https://JoelMWatson.github.io/reading-notes/class-05-reading)

#

## Class 05 Reading: LinkedLists

#### What is a data structure?

A data structure is a way that we store data in a computer like storing values in a linked-lists or an array.

#### How is a Linked List different from an array?

An array is a series of values that you can access at any point in the array. A linked list is a series of values where you only
have access to the head or the tail or both from which point you can iterate through the linked list using the links (references
to the next and/or previous)

#### What is one benefit a Linked List has over an array?

Linked lists have a major benefit over arrays when it comes to inputing data in the middle of the list. The array has to shift many
values around where the linked list only has to change a couple of references

#### What data does a Node hold in a doubly Linked List?

In a doubly linked list a node holds a previous reference, the data/value for the node, and a next reference.

#### What would you use to implement a Linked List data type? (object, function, class, variable…?)

It would be best to use a class to implement a linked-list datatype so you could control the traversal of the list.
