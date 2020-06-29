# read 28
## setState
React components can, and often do, have state. *State can be anything*
`setState()` is the only legitimate way to update state after the initial state setup.

## Props
is a special keyword in React, which stands for properties and is being used for passing data from one component to another. Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.


In React, both this.props and this.state represent the rendered values, i.e. what’s currently on the screen, also in a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component & the state can be initialized by props.

## Data flow
One Way Data flow
state passed from parent component through props it is the idea if data flow this data flow passed down the component tree if you want to pass a data to a parent this function pass to child.