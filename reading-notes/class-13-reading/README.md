#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Bearer Authorization](https://JoelMWatson.github.io/reading-notes/class-13-reading)

---

## Class 13 Reading: Bearer Authorization

#### When is Basic Authorization used vs. Bearer Authorization??

Basic Authorization is used when the user enters their username+password. Bearer
Authentication is used after the initial Basic or OAuth authentication by supplying
the bearer token recieved after basic authorization.

#### What does the JSON Web Token package do?

The JSON Web Token package allows developers to create signed and encrypted tokens
and to verify those tokens, so that they can securely pass information between two
systems (server, client, etc.)

#### What considerations should we make when creating and storing a SECRET?

We should consider that it needs to be consistent accross all jwt signatures and
should be kept secure by storing it in a .env file and accessing it through the
process.env.

More info at [JSONWebToken Docs](https://www.npmjs.com/package/jsonwebtoken)
