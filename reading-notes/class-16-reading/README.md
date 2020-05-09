#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Event Driven Applications](https://JoelMWatson.github.io/reading-notes/class-16-reading)

---

## Class 16 Reading: Event Driven Applications

#### Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?

Some examples of back end-events could be when a user gets signed into the application
or when they create a new post.

#### Why are events sometimes better than asynchronous actions with callbacks?

Events can be better than asynchronous actions with callbacks because you are able
to easily attach multiple listeners to an event to do many different things. This
gets extremely complicated with callbacks as they usually must be called in the
correct order.

#### What does an EventEmitter instance do?

An EventEmitter is the class imported from Nodes events module and is used to raise
events and to listen for/handle raised events inside the application.

#### When is a program’s call stack, event queue, and event loop active?

A programs callstack, event queue and event loop are active the whole time you app
is running. While the initial callstack is being run through, the event loop continuously
checks to see if the callstack is empty. whenever the callstack is empty it will
dequeue an event from the event queue and add it to the callstack.
