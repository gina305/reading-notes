# State and Props

## React Lifecycle
The React lifecycle is made up of component classes and methods that allow you to update UI and application states. The methods that you can use on these classes and event are called lifecycle events. Each component has three phases to its component lifecycle: mounting, updating and unmounting.
1.	Mounting Phase: When a component is created and inserted into the DOM.
2.	Updating Phase: when a component is updated or when the state changes, during the update phase it is re rendered.
3.	Unmounting Phase: the final phase of the life cycle where the component is removed from the DOM.
 
1.	Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
The render method is invoked before the ‘componentDidMount’. ‘ComponentDidMount’ is used to manipulate rendered DOM elements, network requests and so on.
2.	What is the very first thing to happen in the lifecycle of React?
In the React lifecycle, the first thing to happen is to call the constructor for a React component.
3.	Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates:
* constructor
* render
* componentDidMount
* React Updates
* componentWillUnmount

4.	What does componentDidMount do?
ComponentDidMount allows you to execute React code when the component is already placed in the DOM.

| ![React Components](./imgs/chart%20to%20help%20you%20keep%20track%20of%20the%20lifecycle%20events.png) |
|:--:|
| <b>React: Component Lifecycle Events by J. Blankenship (2018)<b> <i>- https://medium.com/. Retrieved from:https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093/|</i>


## React State Vs Props
1.	What types of things can you pass in the props?
You can use props to pass in data (such as data stored in variables) to a React component.
2.	What is the big difference between props and state?
Props allows you to pass data into a component. State is similar to props, but is private and fully controlled by the component.
3.	When do we re-render our application?
To re-render an application, you must use setState(). SetState() let’s React know that the state has changed and calls the render() method again re-render the application on the screen.
5.	What are some examples of things that we could store in state?
State can store data that we want to persist across components. State can store things such as a string, number or object.

