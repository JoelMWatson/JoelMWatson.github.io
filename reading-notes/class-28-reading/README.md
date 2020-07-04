#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [React Context API](https://JoelMWatson.github.io/reading-notes/class-28-reading)

---

## Class 28 Reading: Context API

#### What is the difference between the variables MyContext and MyProvider in the examples above?

The difference between the MyContext variable and the MyProvider variable from the
example is that the MyContext variable is just a reference to a new react context
that was created. The MyProvider variable is an actual component that uses the
context to defined/modified state variables.

#### Why is context useful?

Context is useful because it allows us to pass state variables directly to the
component that needs them without having to pass it to each component as a prop.

#### Can a component outside of a provider get its context?

Components outside the provider will not have access to the same context that is
accessible inside the provider.
