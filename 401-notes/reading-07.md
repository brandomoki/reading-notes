# Bearer Authorization

## Intro to JWT

1. What is a JSON Web Token (JWT)?

- JWT is an open standard (RFC 7519) thisis a compact way of of securely transmitting info from one party to another

1. When should we use JSON Web Tokens?

- Authorization and In formation exchange

1. Claims are expected in which structural component of a JWT?

- Claims are expected to be in the payload component

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?

- The payload is only encoded using Base64 so we shouldnt use private information here. This can be username or other non private data

1. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

- A private key

1. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

-

## JWTs Explained

1. Why use JWT?

- It is a compact way and makes it great to pass in HTML, HTTP environments

1. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

- With it being compact its transmission is fast and being self contained we dont need anything else to use it. Everything is there.

1. What are the three components (the structure) of a JWT signature?

- Header
- Payload
- Signature
