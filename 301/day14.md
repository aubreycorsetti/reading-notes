# Day 14 Notes

## What is OAuth

• What is OAuth?

  > It is an open-standard authorization protocol that describes how unrelated servers and sercers can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

• Give an example of what using OAuth would look like.

  > When you log onto a website and it offers to log on using another websites logon.

• How does OAuth work? What are the steps that it takes to authenticate the user?

  > "Let’s assume a user has already signed into one website or service (OAuth only works using HTTPS). The user then initiates a feature/transaction that needs to access another unrelated site or service. The following happens (greatly simplified):

  1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
  2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
  3. The first site gives this token and secret to the initiating user’s client software.
  4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
  5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
  6. The user approves (or their software silently approves) a particular transaction type at the first website.
  7. The user is given an approved access token (notice it’s no longer a request token).
  8. The user gives the approved access token to the first website.
  9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
  10. The second website lets the first website access their site on behalf of the user.
  11. The user sees a successfully completed transaction occurring.
  12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons). "

• What is OpenID?

  > A single sign-in, vouching for the identities of users.

## Authorization and Authentication flows

• What is the difference between authorization and authentication?

  > Authentication verifies the ID of a user
  > Authorization determines the users access rights

• What is Authorization Code Flow?

  > The authorization code grant type is used to obtain both access
   tokens and refresh tokens and is optimized for confidential clients.
   Since this is a redirection-based flow, the client must be capable of
   interacting with the resource owner's user-agent (typically a web
   browser) and capable of receiving incoming requests (via redirection)
   from the authorization server.

• What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

  > Introduces a secret created by the calling application that can be verified by the authorization server

• What is Implicit Flow with Form Post?

  > Requests and obtains tokens through the front channel, without the need for secrets or extra backend calls

• What is Client Credentials Flow?

  > Authenticates and authorizes the app rather than a user, they pass along their Client ID and Client Secret to authenticate themselves and get a token.

• What is Device Authorization Flow?

  > The device asks the user to go to a link on their computer or smartphone and authorize the device.

• What is Resource Owner Password Flow?

  > Requests that users provide credentials (username and password), typically using an interactive form

### Things I want to know more about

> I would like to learn about how to create a log in

### Sources

https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html

https://auth0.com/docs/get-started/authentication-and-authorization-flow

Click to return [Home!](../README.md)
