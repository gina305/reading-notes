# Readings: Introduction to React and Components

## Component-Based Architecture

1. What is a “component”?
A component is a modular, reusable software object that encapsulates functionality and behaviors.
2. What are the characteristics of a component?
A component can be exported to a higher-level interface and can interact with other components. It can be exported deployed independently and accepts arbitrary inputs called "props:
3. What are the advantages of using component-based architecture?
The main advantage of using a component-based architecture is that  it provides:
* Ease of deployment - It’s easier to replace a component without affecting others
* Ease of development - It’s easier to develop one component without affecting other components
* Reduced cost - The use of third-party components allows you to spread the cost of development and maintenance.
* Reusability- Reusable components allow the spread of development and maintenance costs across several applications or systems.
* System maintenance and evolution - Components make it easy to change/update individual components without affecting the system as a whole.
* Flexibility through independence - The independence of components increases productivity in software development.

## What is Props and How to Use it in React

1. What is “props” short for?
"Props" stands for properties. Properties are object arguments that contain data for use by a component.
2. How are props used in React?
In React, components use props and JSX to render elements to a page. For example, you can define a component that renders a user’s name based on the “name” property passed into the “Welcome” component. With this component, a custom welcome message will be displayed on the webpage.

| ![React Components](./imgs/Hello%20World%20in%20React%202022-04-09%2022-37-24.png) |
|:--:|
| <b>Image Credits - reactjs.org. Retrieved from: https://reactjs.org/docs/components-and-props.html</b>|

3. What is the flow of props?
Props information flow from parents to children in React.
