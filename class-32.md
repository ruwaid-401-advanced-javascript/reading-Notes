# read 32

## Custom Hooks
* mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value)
* Unlike a React component, a custom Hook doesn’t need to have a specific signature
* Hooks are exported as a function
* Hooks are imported into components.

## useReducer Hook
* alternative to `useState`.
* Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method
* optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

## React Hooks with Async-Await  
* We cannot use 'async' keyword with 'useEffect' callback method. It will result in race conditions.  
* we should fetch our data from an API then updating our 'setResult' state  
* React.useEffect method will only run when our 'state' got change.  