# read 11


## User Modeling
Modern web applications need to model sensitive information about their users. When a users provides an applications with sensitive information, they are trusting that it will not be leaked are misused. 

## Cryptography 
Cryptography is the science which studies methods for encoding messages so that they can be read only by a person who knows the secret information required for decoding, called the *key*
which include the *cryptanalysis*
### cryptanalysis
is the science of decoding a encoded method without having the proper key.

## Hashing Algorithms
Cryptographic Hash Algorithm takes a piece of data and produces a hash that is deliberately difficult to reverse.
* if the same data is entered to the hashing algorithm the *same hash is produced*, 
* Hash algorithms are often used for checking the integrity of data.

## cypher algorithms
Cypher Algorithm takes a piece of data and a key and produces encrypted data. Later the encrypted data *can be reversed* into the original data by decrypting it using the same key.
* user token can be created by a *random unique string* (tokenseed) with a user account,
* encrypting the tokenseed with a unique key only the server knows, so we can send the encrypted key to the client,
* client send a request with the encrypted key, and the server decode the key back to the tokenssed, and send the data.

## Basic authorization,
is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.
* they are joined by `:` 
* and "base 64encoded" and placed after the string,
* the server can return the username and password, if the combination is *valid*,
* the server responds with a validation response, which lets the user to re-authenticate with sending the user name and password every time, 


## JSON Web Token?
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
* This information can be verified and trusted because it is *digitally signed*.
* JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

### When should you use JSON Web Tokens?
1. Authorization
2. Information Exchange