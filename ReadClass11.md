## [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
* What is OAuth?
  * > OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential`>-https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html`
* Give an example of what using OAuth would look like.
  * User can use their gmail account to register a lot third-party website
* How does OAuth work? What are the steps that it takes to authenticate the user?
>1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
>2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
>3. The first site gives this token and secret to the initiating user’s client software.
>4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
>5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is >asked to approve the authorization transaction to the second website.
>6. The user approves (or their software silently approves) a particular transaction type at the first website.
>7. The user is given an approved access token (notice it’s no longer a request token).
>8. The user gives the approved access token to the first website.
>9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
>10. The second website lets the first website access their site on behalf of the user.
>11. The user sees a successfully completed transaction occurring.
>12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).>-https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html

* What is OpenID?
  * Another security technology about authotication, mainly for humans logging into machines.

## [Authorization and Authentication flows](https://auth0.com/docs/flows)
* What is the difference between authorization and authentication?
  * Authentivation is the process to verify who the user is. Authorization is to verify what users have access to
* What is Authorization Code Flow?
  * Exchange an Authorization Code for a token
* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  * >During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).>-https://auth0.com/docs/flows
* What is Implicit Flow with Form Post?
  * >As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.>-https://auth0.com/docs/flows
* What is Client Credentials Flow?
  * >With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4), in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.>-https://auth0.com/docs/flows/client-credentials-flow
* What is Device Authorization Flow?
  * >With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. To do this, device apps use the Device Authorization Flow (ratified in OAuth 2.0), in which they pass along their Client ID to initiate the authorization process and get a token.>-https://auth0.com/docs/flows/device-authorization-flow
* What is Resource Owner Password Flow?
  * Process that requests users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.

[Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react)


## Things I want to know more about
[<--Back](README.md)