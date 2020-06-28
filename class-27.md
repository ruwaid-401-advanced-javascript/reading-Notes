# read 27

# React Testing  
  There are a few ways to test React components. 
* Snapshots 
  * Make assertions on the exact rendered markup (with content) at any state of the application.

* Mounting 
  * Executes the full component and children. Allows for inspection of rendered Virtual DOM as well as the current state

* Render Testing 
  * Similar to snapshots, but allows for jQuery-like inspection of the virtual DOM tree

* Shallow Testing 
  * Executes and renders the called/container component, but does not compose children.

## Deployment
React in development mode uses node service to create live website, this is not what actually gets deployed if you want to deploy your website online.`npm run build` excuted from the root folder in React application.

### Deploying to 
* AWS Amplify
* Netlify
