Wednesday August 7, 2022

What is OAuth?
- authorization framework that allows you to consent to an application interacting with another on your behalf without having to reveal your password


Give an example of what using OAuth would look like.
- login 


How does OAuth work? What are the steps that it takes to authenticate the user?
-  the first site connects to the second site using OAuth, providing user's verified identity then the second site generates a 1 time token and secret. The first site gives the token and secret to the initiating user's client software. After the client's software gives request token and secret to authorization provider. Client may be asked to authenticate if not done already. Client asked to approve authorization to the second site. The user/user's software approves transaction to the first site. User's given approved access token. User gives approved access token to the first site. The the first site gives access token to the second site as proof of authentication.The second site lets the first site access their site on user's behalf. And lastly the user sees successfully completed transaction occurring.


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