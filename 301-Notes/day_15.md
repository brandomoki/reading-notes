# Authentication

## What is OAuth

1. What is OAuth?
    * OAuth is an open-standard authorization protocol. third-party delegated autherization

1. Give an example of what using OAuth would look like.
    * allowing users to logon using a third parties logon services

1. How does OAuth work? What are the steps that it takes to authenticate the user?
    1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
    1. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
    1. The first site gives this token and secret to the initiating user’s client software.
    1. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
    1. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
    1. The user approves (or their software silently approves) a particular transaction type at the first website.
    1. The user is given an approved access token (notice it’s no longer a request token).
    1. The user gives the approved access token to the first website.
    1. The first website gives the access token to the second website as proof of authentication on behalf of the user.
    1. The second website lets the first website access their site on behalf of the user.
    1. The user sees a successfully completed transaction occurring.
    1. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).
    <!-- credit Roger Grimes and Josh Fruhinger -->

1. What is OpenID?
    * OpenId is a single sign on that vouches for the user for multiple site

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
    * authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to

1. What is Authorization Code Flow?
    * It exchanges a Auth code for a token

1. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
    * The proof key is used to exchange for code

1. What is Implicit Flow with Form Post?
    * As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets

1. What is Client Credentials Flow?
    * This method authorizes the app rather than the user

1. What is Device Authorization Flow?
    * This method lets the user use a link to sign on using a different more user friendly device

1. What is Resource Owner Password Flow?
    * user enter username and password into a form to gain access
