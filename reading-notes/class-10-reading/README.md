#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Authentication & Encryption](https://JoelMWatson.github.io/reading-notes/class-10-reading)

#

## Class 10 Reading: Authentication & Encryption

#### Why is authentication important?

Authentication is important because it allows us to make sure a person has the
authority to do what they request. (EX. Don't allow user to create post unless
logged in.

#### Why should we be careful about storing a user’s password?

You should be careful when storing users passwords for multiple reasons. One of
the big reasons its important to be careful is because people often reuse their
passwords and if your data is ever exposed you could allow malicious actors to
access the users data with other online services.

#### What is the difference between hashing and encryption?

Hashing and encryption are both forms of securing information, the difference is
that with encryption, there is a way to decrypt the data at the end. With hashing,
you end up with a hash of the data which is always consistent, but not reversable.

#### What is the difference between encryption and encoding?

The difference between encryption and encoding is that encoding is done with a
publicly available algorithm to allow easy reversal. Encryption is not able to be
reversed without a private key so only select people can access it.

#### What is a token used for?

A token is used for authorization so you know someone is who they say they are,
and also sometimes as a way to transmit some data.
