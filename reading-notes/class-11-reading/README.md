#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Stacks & Queues](https://JoelMWatson.github.io/reading-notes/class-11-reading)

---

## Class 11 Reading: Stacks & Queues

#### Come up with an application scenario where you would want to use a stack.

An application where you would want to utilize a stack would handle a LIFO situation
like an app that tracked clean plates at a restaurant. Since it doesnt matter how
long a plate sits in the stack, you always just take from the top of the stack of
plates and also place newly cleaned plates onto top of the stack.

#### Come up with an application scenario where you would want to use a queue.

An application where you would want to utilize a queue would handle a FIFO situation
like an app that tracked produce at a grocery store that was in the back storage and
what was on the shelves for sale. The first produce received would be the first produce
put out to sell on the shelves, the last produce received would be the last produce
to be put out on the shelves.

#### Why are pop, push, enqueue and dequeue always O(1)?

Pop, push, enqueue, and dequeue always take O(1) time because with push and pop, no matter
how many elements are in the stack you always have the reference to the top of the stack so
interacting with the top of the stack can be done in constant time. Similarly with enqueue
and dequeue, you always have a reference to the back, and front of the que so they can also
be interacted with in constant time reguardless of the number of elements in the que.

#### Why do stacks and queues not have traversal or searching operations?

Queues and stacks do not have traversal or searching operations because for their use cases
queues and stacks are not concerned with the values that they store but more the order that
they store/read the values.
