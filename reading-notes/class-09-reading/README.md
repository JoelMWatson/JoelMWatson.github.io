#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Joins & Virtual Joins](https://JoelMWatson.github.io/reading-notes/class-09-reading)

---

## Class 09 Reading: Joins & Virtual Joins

#### Describe a use-case where param middleware would come in handy.

One use-case where param middleware would come in handy would be authentication middleware run
whenever the id token is supplied as a param.

#### What are the two ways to add middleware in-between Mongoose and MongoDB interactions?

The two ways to add middleware between Mongoose and MongoBD interactions are by using the
pre or the post hooks.

#### What is the difference between a join by reference and a virtual join?

A join by reference differs from a virtual join in that the join by reference is actually defined
in the schema itself as a field of the object of the ObjectID type. In a virtual join, the options
are given to the schema to allow virtuals and then below the schema, you set up your virtual field.

#### What do localField and foreignField mean?

The localField and foreignField are used to tell the virtual join which field in the local table
(localField) should match to which field in the remote table (foreignField).
