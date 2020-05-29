# read 6

## HTTP
The Hyper Text Transfer Protocol (HTTP) is a stateless request-response application layer protocol
the World Wide Web is based on HTTP. 
* the clients are hosts that make the request to the server, 
* HTTP is serving .html, image files,videos, .json, .xml ...etc. 
* the HTTP request is formatted in text and transferred using TCP.
* it contains METHOD, URL and HTTP VERSION. HEADERs are a key-value pair, seperated using **semicolon**, and each line with **newline character**.

### HTTP Request
is a packet of Information that one computer sends to another computer to communicate something

### HTTP Response
A client (browser) submits an HTTP request to the server; then the server returns a response to the client. The response contains status information about the request and may also contain the requested content


## REST
REST is acronym for REpresentational State Transfer

* RESTful Endpoint: `http://api.server.com/api/v1/people`
  * http:// - Protocol/Scheme
  *  api.server.com - Domain or Server
  * /api/v1 - API Endpoint
  * /people - The resource (This identifies a collection: all people)
  * /people/12345 - A more specific resource: The person with id 12345


## Swagger
Swagger is a set of open-source tools built around the OpenAPI Specification that can help you design, build, document and consume REST APIs. The major Swagger tools include:
### Swagger Editor 
browser-based editor where you can write OpenAPI specs.
### Swagger UI 
renders OpenAPI specs as interactive API documentation.
### Swagger Codegen 
generates server stubs and client libraries from an OpenAPI spec.

### What is swagger used for?
Swagger is a set of rules (in other words, a specification) for a format describing REST APIs. it can be used to share documentation among product managers, testers and developers, but can also be used by various tools to automate API-related processes