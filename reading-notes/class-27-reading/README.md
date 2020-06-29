#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Custom Hooks](https://JoelMWatson.github.io/reading-notes/class-27-reading)

---

## Class 27 Reading: Custom Hooks

#### Why do custom hooks need the "use" prefix?

Custom hooks need to have the "use" prefix because it allows react to recognize
that this function is actually a custom hook and can return stateful variables.

#### What do custom hooks usually do?

Custom hooks allow you to modularize your code much further than state components.
It is especially useful for separating business logic from UI logic.

#### Using the links above, list one custom hook that you would be interested in trying/using.

The useFormState hook from the react-use-form-state package seems interesting. It
looks like it drastically reduces the code necessary to process form data.
