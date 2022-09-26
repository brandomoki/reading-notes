# Authentication

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

  - This is a way of encrypting passwords when storing them.

1. What is Bcrypt?

  - Bcrypt is a way of encrypting passwords with a techinique called key stretching.


1. Why might you use something like Bcrypt?

  - Bcrypt lengthens the hasing process so it takes considerably more time to brute force a password.

## Basic Auth

1. What is Basic Authentication?

  - Its a way for an HTTP request to provide a username and password

1. What properties are necessary in the header of a Basic Auth request?

  - A form of authorization that take basic credential, this is where credential are base64 encoded and joined by single colon

1. How are username:password in Basic Auth encoded?

  - Base64

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.

  - The process is performed by the user or site providing a username and password that is base encoded for transport

1. How should your error messaging respond (both HTTP and HTML)? Why?

  - error messages should be generic. We dont want to help the brute force attacker

1. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

  - [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
