Wednesday August 7, 2022

What is OAuth?
- authorization framework that allows you to consent to an application interacting with another on your behalf without having to reveal your password


Give an example of what using OAuth would look like.
- login 


How does OAuth work? What are the steps that it takes to authenticate the user?
-  The first website connects to the second website on behalf of the user. Then the second site generates a one-time token and a one-time secret unique to the transaction and parties involved.


What is OpenID?
- Allows you to use an existing account to sign in to multiple websites, without needing to create new passwords.


What is the difference between authorization and authentication?
- Authorization is when you have permission to access something
- Authentication is when you have to prove that is valid before you get permission to access


What is Authorization Code Flow?
-  used to obtain an access token to authorize API requests


What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
- the recommended form of authenticating RingCentral users and exchanging tokens in client-side applications


What is Implicit Flow with Form Post?
- uses OIDC to implement web sign-in 


What is Client Credentials Flow?
- permissions are granted directly to the application itself by an administrator.


What is Device Authorization Flow?
- input-constrained devices that connect to the internet, rather than authenticate the user directly


What is Resource Owner Password Flow?
- allows exchanging the username and password of a user for an access token and, optionally, a refresh token.