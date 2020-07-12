# read 37
## The combineReducers
The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.
It is pulling in more than one reducer from source and creating a keyed object from them.  
The resulting reducer calls every child reducer and gathers their results into a single state object. The state produced by `combineReducers()` namespaces the states of each reducer under their keys as passed to `combineReducers()`

## actions
Each reducer technically has it’s own actions and creators. and If an action is dispatched with both reducers recieving it, both would respond to it.


## Concept
The most common state shape for a Redux app is a plain Javascript object containing “slices” of domain-specific data at each top-level key,



