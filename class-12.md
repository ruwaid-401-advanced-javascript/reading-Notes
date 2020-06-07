# read 12

## Open Authorization
OAuth (Open Authorization) is an open standard for token-based authentication and authorization on the Internet. OAuth, allows an end user's account information to be used by third-party services, such as Facebook, without exposing the user's password.

## How does OAuth authentication work?
It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

* OAuth work through a series of *handshakes*, the app asks the user if it is ok to login as them at some remote service and then begins the process of authentication and access.

## Access Code
The authorization code grant is used when an application exchanges an authorization code for an access token. After the user returns to the application via the redirect URL, the application will get the authorization code from the URL and use it to request an access token. This request will be made to the token endpoint.

* Request Parameters The access token request will contain the following parameters.

* grant_type (required) The grant_type parameter must be set to “authorization_code”.

* code (required) This parameter is the authorization code that the client previously received from the authorization server.

* redirect_uri (possibly required) If the redirect URI was included in the initial authorization request, the service must require it in the token request as well. The redirect URI in the token request must be an exact match of the redirect URI that was used when generating the authorization code. The service must reject the request otherwise.
