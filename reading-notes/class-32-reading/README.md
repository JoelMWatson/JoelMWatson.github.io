#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Redux - Async Actions](https://JoelMWatson.github.io/reading-notes/class-32-reading)

---

## Class 32 Reading: Redux - Async Actions

#### Reading Notes

Redux asynchronous actions are handled with thunk middleware (we use redux-thunk).
Redux thunk essentially checks every action that you dispatch to see if it is a
regular action object or if it is a function. If it is a function, rather than just
dispatching the action, it calls the function and then dispatches the return value
from the function. This allows you to handle async actions by calling the async
function, awaiting the result and then dispatching
