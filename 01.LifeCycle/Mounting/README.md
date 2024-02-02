
### Lifecycle of Components
Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.    
    
The three phases are: Mounting, Updating, and Unmounting.    
    
Mounting    
Mounting means putting elements into the DOM.    

React has four built-in methods that gets called, in this order, when mounting a component:    
    
constructor()    
getDerivedStateFromProps()    
render()    
componentDidMount()    
The render() method is required and will always be called, the others are optional and will be called if you define them.    