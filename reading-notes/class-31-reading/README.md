#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Redux - Combined Reducers](https://JoelMWatson.github.io/reading-notes/class-31-reading)

---

## Class 31 Reading: Redux - Combined Reducers

#### Reading Notes

Redux reducers are incredibly useful but as your application grows and your state
object grows, the complexity of your reducer can also grow. To avoid this complexity,
we follow the single responsibility principle and have a different reducer for each
piece of state and separate them into their own files. This is much easier to maintain,
but we now have a new problem. You have to import all these reducers into each component
that needs them. To simplify this, redux has the combine reducers function which
takes all of your reducers and exports them as one large reducer object off of which
you can deconstruct any or all of your reducers.
