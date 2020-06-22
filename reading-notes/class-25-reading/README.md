#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [HashTables](https://JoelMWatson.github.io/reading-notes/class-25-reading)

---

## Class 25 Reading: HashTables

#### Is a HashTable useful for search or sorting operations? Why?

HashTables are very useful for storing and retrieving data when the order is not
important. This is because they determine the location of the data using a hash
which will consistently calculate the same location for the same piece of data.
For this reason they are not useful for searching or sorting.

#### What makes a good hash function?

A good hash function has to be consistent, always creating the same output for any
given input. This is important when you want to store or retrieve anything in
the table.

#### Why should you try to reduce the number of collisions?

Reducing the number of collisions in a hashtable improves its worst case runtime
since every collision results in multiple elements in a bucket.

#### What is stored at each index of a HashTable? Why?

Each index of a hashtable holds a bucket. This allows each index of the hashtable
to store multiple elements in the case of a collision.
