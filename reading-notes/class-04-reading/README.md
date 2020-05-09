#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Interfaces & Middleware](https://JoelMWatson.github.io/reading-notes/class-04-reading)

---

## Class 04 Reading: Interfaces & Middleware

#### What makes an interface useful?

Interfaces are useful because they simplify how you interact with something (like a database)
and they can also simplify how the data is returned.

#### Why is middleware called middleware?

Middleware is called middleware because it happens in the middle of the opperation. For instance
you can use middleware to authenticate a user before preforming the command.

#### Fundamentally, what does it mean to have a mock of something? Why is this useful?

To have a mock of something is to create a fake instance of that thing in order to interact with it
when you are testing. It is useful when you are testing against a database or an API so you dont need
to keep connecting or wasting api credits.

#### What does it mean to have a mock database?

Having a mock database means that you create a database with the same structure as your real database
but unlike your real database, it only exists for the lifetime of the test
