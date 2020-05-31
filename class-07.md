# read 7

## Express
Express is a JS Library, that is a event driven system, the routing is straight forward,also Express is a routing and middleware web framework that has minimal functionality of its own: 

* In the request we have parameters or query strings, 
* the response is responsible for sending data back to the browser, 
* it has `send()` and `status()` methods.
**An Express application is essentially a series of middleware function calls.**

## Middlewares
Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.
middlewares are used for logging, Dynamic Model Loading, Browser, location, specific content and consistant data transition. 

**If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.**


## Routing
Routing refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing, see Basic routing.

You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD. You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function

These routing methods specify a callback function (sometimes called “handler functions”) called when the application receives a request to the specified route (endpoint) and HTTP method. In other words, the application “listens” for requests that match the specified route(s) and method(s), and when it detects a match, it calls the specified callback function.

In fact, the routing methods can have more than one callback function as arguments. With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.

## Test Pyramid
Server Testing crosses boundaries
* Units: Server Internal Functions
    - Mock any integrations (like data fetching)
* Integration: How it connects to other services
    - Really connect to other services (hard dependencies)
* Acceptance
    - The server might be a dependency of some other test