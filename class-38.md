# read 38


## thunk

A thunk is a function that wraps an expression to delay its evaluation.

## Redux Thunk middleware

It allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods dispatch and getState as parameters.

## React Suspense?
Suspense is a new React feature that was announced recently at the JSConf Conference in Iceland. It aims to help with handling async operations respectively in regard to CPU power and data fetching.

## Asynchronous Redux Actions Using Redux Thunk  
  The most common use-case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data.  
  Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.
 