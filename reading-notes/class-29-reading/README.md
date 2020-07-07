#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Application State with Redux](https://JoelMWatson.github.io/reading-notes/class-29-reading)

---

## Class 29 Reading: Application State with Redux

#### Why would you wrap your entire application within a context?

One reason to wrap your entire state in a context is because then all your
descendant components will have access to those state variables.

#### What is the purpose of a reducer?

The purpose of a reducer is to take the current state and an action, and update
the state with the given action.

#### What does an action contain?

An action contains two things, the action type telling it which action to do, and
the action payload, which is the data to use for the action.

#### Why do we need to copy the state in a reducer?

Reducers need a copy of state so they can update it with the action or return the
state if no actions need to be taken.
