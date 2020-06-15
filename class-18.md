# read 18

### Socket.IO
Socket.IO is a JavaScript library that helps improving work with Web-Sockets. Socket.IO allows to use additional features such as sending data to large number of sockets at the same time (broadcasting) or storing the data.

The main idea behind Socket.IO is the ability to send and receive any events with any data .

* Web Sockets A communication Protocol which provides bidirectional communication between the Client and the Server over a TCP connection, WebSocket remains open all the time so they allow the real-time data transfer. When clients trigger the request to the Server it does not close the connection on receiving the response, it rather persists and waits for Client or server to terminate the request.


### socket handshake
The handshake in Socket.IO is like any other information technology related handshake. It is the process of negotiation, which in Socket.IO's case, decides whether a client may connect, and if not, denies the connection.

* Socket.io It is a library which enables real-time and full duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts, each of which use WebSockets, but also provide additional functionality such as broadcasting, namespacing, and other means of segmenting connected clients into groups.

* Connections With TCP, you connect directly to a server with a keep-alive type of connection.

* With Socket.io, you connect to a server over HTTP. The session is “kept alive” through it’s internal use of the WebSocket Protocol, with session information being preserved.

* Messaging Standard node events are sent with emit() and received with on() … Socket.io uses the same methodology/terminology.

### Connections
With TCP, we can connect directly to a server with a keep-alive type of connection.

With Socket.io, you connect to a server over HTTP. The session is “kept alive” through it’s internal use of the WebSocket Protocol, with session information being preserved.