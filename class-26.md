# read 26

## React
- React is a JavaScript library.

### The smallest React example looks like this:
`ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);`

### JSX
it is a syntax extension to JavaScript.
`const element = <h1>Hello, world!</h1>;`

### Why JSX?
React embraces the fact that rendering logic is inherently coupled with other UI logic: 
* how events are handled
* how the state changes over time, 
* how the data is prepared for display.


### Rendering Elements
* Elements are the smallest building blocks of React apps.
* Unlike browser DOM elements, React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements.
* React elements are *immutable*. 
* React Only Updates What’s Necessary

## SASS
Syntactically awesome style sheets (Sass) is an extension of CSS that enables you to use things like variables, nested rules, inline imports and more. 
* Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.
* Sass is completely compatible with all versions of CSS.
