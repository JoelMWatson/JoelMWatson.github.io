#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Express Routers](https://JoelMWatson.github.io/reading-notes/class-08-reading)

---

## Class 08 Reading: Express Routers

#### What is a benefit to using express.Router()?

One benefit of using express.Router() is the ability to create separate router objects for each object type.
You are then able to attach middleware to specific routers and rather than tying them to the entire app router.

#### When I say that top-down order matters in Express, what does that mean?

Top-down order in terms of express quite literally means that the order runs from top to bottom so attaching
middleware after creating a router will not run the middleware for those routes created above it.

#### Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?

We call a model class rather than calling MongoDB operations directly because having a "wrapper class" like the model
allows us another layer of abstraction from the database meaning users of the model class dont need to know anything
about the database structure or even what database we are using. They have a simple interface to work with and thats
all they need to know.
