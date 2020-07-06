# read 33

## Context API
Context: It is provides a means of passing state down the component tree through a Provider/Consumer relationship, is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. Also we can avoid passing props through intermediate elements.

* If you only want to avoid passing some props through many levels, the component composition is often a simpler solution than context.    

## Before Use Context  
* Context is primarily used when some data needs to be accessible by many components at different nesting levels.  
* Apply it sparingly because it makes component reuse more difficult. 

## React.createContext
When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.