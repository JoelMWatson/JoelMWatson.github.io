#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes)

---

## Class 17 Reading: TCP Server

#### What do the layers in the OSI and TCP/IP models represent?

The layers in the OSI and TCP/IP models represent different actions in the process
of transfering the data.

#### What is the benefit of transforming data into packets?

The benefit of transforming data into packets is that each packet is chunked to
about one kilobyte in size making them easy to send over the internet.

#### UDP is often referrered to as a connectionless protocol. Why is this?

UDP is referred to as a connectionless protocol because with UDP you do not establish a strong secure connection between the sending and recieving serverss

#### Can a socket server application have multiple socket connections?

There can be multiple socket connections on a single socket server application.

#### Can a socket connection application be connected to multiple socket servers?

A socket connection application can only connect to one socket server.

#### Can an application be both a socket server and a socket connection?

You can create an application that is serves as both a socket server and a socket
connection as long as they do not use the same port at the same time.
