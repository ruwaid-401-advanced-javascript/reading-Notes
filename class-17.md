# read 17


## Events Queues
Events Queues, NodeJS's architecture is build around the use of events, the EventEmitter constructor emits events as instances, it is also a great way to handle async events, functions can be registered as event listeners. multiple services can be connected by various protocols using proprietary APIs. this is done by using a queue.

## Internet Protocol 
Internet Protocol Suite The Internet Protocol Suite is the conceptual model for the protocols used by the internet. It is often referred to as TCP/IP because the IP and TCP were the original protocols in the suite. The Internet Protocol Suite is described using four layers - Link, Internet, Transport, and Application. Web developers often reference the Internet Protocol Suite model when discussing network communication and data exchange.

TCP The Transmission Control Protocol (TCP) is widely used by application layer protocols in the Internet Protocol Suite. TCP creates a two way communication between two hosts and provides reliable, ordered, and error checked byte streams between the applications. TCP data transfers manage network congestion and use flow control to limit the rate a sender transfers data to guarantee reliable delivery. Each IP packet between the hosts carries a single TCP Segment. A TCP segment is made up of header and data sections.


## How does a TCP server work?
The Internet works by using a protocol called TCP/IP, or Transmission Control Protocol/Internet Protocol. In base terms, TCP/IP allows one computer to talk to another computer via the Internet through compiling packets of data and sending them to right location.

## Notes
OSI Model Programmers and engineers have been able to network computers since the early 1970s. As the needs of networked computers evolved, there where many solutions developed to connect two ore more computers together and share information between them. Over time, several different conceptual models have also been developed to help describe the different networking solutions. In the mid 1980s the “Open Systems Interconnection Reference Model” (OSI model) was developed as a seven layer model. This seven layer OSI model has continued to accurately describe the different processes in computer networking, and is still widely used as a point of reference while working in networked systems today. A developer or engineer is usually responsible for the goals of a specific layer and communicating with the layer above and below. Not every computer network solution uses all seven layers, for example HTTP skips the Presentation and Session layers and lives directly on top of the Transport layer