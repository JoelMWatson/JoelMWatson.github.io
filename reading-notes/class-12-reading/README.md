#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [OAuth](https://JoelMWatson.github.io/reading-notes/class-12-reading)

#

## Class 12 Reading: OAuth

#### What's a benefit of using OAuth instead of your own basic authentication?

One of the benefits of using OAuth instead of your own basic authentication is that,
it allows you to delegate authorization to a trusted third party also allowing the
user to be authenticated without creating a whole new account.

#### Write the following steps in the correct order:

- Ask the client if they want to sign in via a third party
- Redirect to a third party authentication endpoint
- Receive authroization code
- Make a request to a third-party API endpoint
- Make a request to the access token endpoint
- Receive access token
- Register your application to get a client_id and client_secret

#### What can you do with an authorization code?

Authorization codes allow a server to request specific secret information about a
user from a third party where the user has allowed us access.

#### What can you do with an access token?

Access tokens allow us to make requests to a third party api on behalf of a user.
