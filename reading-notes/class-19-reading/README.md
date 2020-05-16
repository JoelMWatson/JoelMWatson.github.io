#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> #### Class 19 - [Message Queues](https://JoelMWatson.github.io/reading-notes/class-19-reading)

---

## Class 19 Reading: Message Queues

#### What is the main benefit of a message queue server?

Some of the main benefits of a message queue server are the ability for clients to
"catch up" and pull down any information they may have missed while they were not
connected and the ability for clients to subscribe to only specific queues.

#### Why might we want to initiate messages from an HTTP request?

One reason to initiate the messages from an HTTP request is that it enables
asynchronous communication.

#### Is the Message Queue Server a socket.io client, a socket.io server, or an api server?

The message queue is a socket.io server that is waiting for the requests (messages)
from the api server and sending them to the appropriate clients and then waiting
to confirm they got it.
