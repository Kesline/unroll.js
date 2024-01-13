### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?

React Router is a powerful library that facilitates navigation in a React application. It allows developers to create a single-page application with navigation capabilities, which means that they can define routes and the components associated with them. This makes it possible to display different components based on the URL, providing a seamless user experience




- What is a single page application?

A single-page application is a type of website or web application that updates the content on the current page dynamically, instead of loading entirely new pages from the server. This approach provides a more seamless and responsive user experience, as it allows for content to be updated without requiring a full page reload.


- What are some differences between client side and server side routing?
Client-Side Routing: The routing is handled on the client side (in the browser). Navigation between different views or components occurs without a full page reload.
Server-Side Routing: The server determines the content to be displayed and sends a full page in response to each navigation request. Each navigation results in a round trip to the server.



- What are two ways of handling redirects with React Router? When would you use each?

Using <Redirect> component: This is used when you want to redirect the user based on certain conditions within the component.
Programmatic navigation: Using history.push or history.replace to change the URL programmatically. This is useful when you want to redirect based on some logic outside the rendering components.


- What are two different ways to handle page-not-found user experiences using React Router? 

Using a <Route> with no path: Create a <Route> with no specified path that will match any location. This route should be placed at the end of your route configuration.
Custom 404 component: Create a dedicated component to be displayed when none of the routes match. It acts as a catch-all for undefined routes.


- How do you grab URL parameters from within a component using React Router?
...


- What is context in React? When would you use it?

Context is a powerful feature in React that enables the sharing of values, such as user authentication state, themes, and more, between components without the need to pass props explicitly through each level of the component tree. This is especially useful when certain data needs to be accessed by many components at different nesting levels, as it simplifies the process and reduces the amount of code that needs to be written.



- Describe some differences between class-based components and function
  components in React.

  Syntax: Class components use the class syntax, while function components are defined using regular JavaScript functions.
State and Lifecycle: Class components can have state and lifecycle methods, while function components can use the useState hook for state and other hooks for lifecycle functionality.
Access to this: Class components use this to refer to the instance of the component, while function components don't have a this context.



- What are some of the problems that hooks were designed to solve?

Complexity of State Logic: Hooks provide a more direct way to handle state logic without the need for class components and lifecycle methods.
Reusing Stateful Logic: Hooks make it easier to extract and reuse stateful logic across different components.
Side Effects: Hooks like useEffect address the management of side effects in functional components, replacing lifecycle methods like componentDidMount and componentDidUpdate.
Readability and Reusability: Hooks contribute to cleaner and more readable code, allowing developers to organize and reuse logic more effectively in functional components.
