# read 16

## Event Driven Applications

> Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision. 


### concepts of the Event-Driven Programming:

1. An Event Handler is a callback function that will be called when an event is triggered.
2. A Main Loop listens for event triggers and calls the associated event handler for that event.

### Emitting Events
EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away.

* In node.js an event can be described as a **string with a corresponding callback**.
* An event can be "emitted" multiple times 
* we can choose to only listen for the first time event is emitted.

#### The EventEmitter class is defined and exposed by the events module:  
`const EventEmitter = require('events').EventEmitter;`  