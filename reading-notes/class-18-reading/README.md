#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Socket.io](https://JoelMWatson.github.io/reading-notes/class-18-reading)

---

## Class 18 Reading: Socket.io

#### What does it mean that web sockets are bidirectional? Why is this useful?

When it is said that web sockets are bidirectional, it means that they can communicate
to the server from the socket, as well as to the socket from the server. This is
useful when you want to broadcast something to all of the clients from the server.

#### Does socket.io use HTTP? Why?

Socket.io uses both TCP and HTTP. TCP is used for the data transfering while the
HTTP is used to keep the connection alive and authenticated.

#### What happens when a client emits an event? What happens when a server emits an event?

When a client emits an event in socket.io, the connected server will respond to
the event. When the server emits an event, all the connected sockets will respond
to it;
