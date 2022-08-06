# Authentication

What is OAuth?
* OAuth is an open-standard authorization protocol that allows unrelated servers and services to safely authenticate access to their assets without actually sharing user logon credentials. 
Give an example of what using OAuth would look like.
* An example of OAuth is using a current Google account to create a new account on an unrelated company website. 
How does OAuth work? What are the steps that it takes to authenticate the user?
* To complete the authentication protocol, an authorization request is made to Google using OAuth. Google then responds with an access token that the server can use to access the protected resource.
What is OpenID?
* OpenID is a simple identity layer on top of the OAuth 2.0 protocol that allows clients to verify the identity of the end user, as well as to obtain basic profile information about the End-User in a REST-like manner.
 ____________________________________________________

Authorization and Authentication flows
What is the difference between authorization and authentication?
* Authentication defines whether or not you gain access to a resource. Authorization defines what you can or cannot do after you are allowed to access a resource (such as read, modify, etc).
What is Authorization Code Flow?
* Authorization code flow is the process by which OAuth is used to exchange an authorization code for a token.
What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
* The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier.
What is Implicit Flow with Form Post?
* Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. 
What is Client Credentials Flow?
* Credentials flow is when machines communicate to each other to pass along their client id and client secret to authenticate themselves and get a token.
What is Device Authorization Flow?
* Device Authorization flow is an extension to the original OAuth that allows you to obtain access tokens on devices where the user has limited possibilities to enter its credentials.
What is Resource Owner Password Flow?
* The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. 

