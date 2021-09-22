# React Docs - thinking in React

1- How would you break a mock into a component heirarchy?
Step 1: Break The UI Into A Component Hierarchy
Step 2: Build A Static Version in React
Step 3: Identify The Minimal (but complete) Representation Of UI State
Step 4: Identify Where Your State Should Live
Step 5: Add Inverse Data Flow


2- What is the single responsibility principle and how does it apply to components?
The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

3- What does it mean to build a ‘static’ version of your application?
Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies

4-Once you have a static application, what do you need to add?
To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

5- What are the three questions you can ask to determine if something is state?
[x]- Is it passed in from a parent via props? If so, it probably isn’t state.
[x]-Does it remain unchanged over time? If so, it probably isn’t state.
[x]-Can you compute it based on any other state or props in your component? If so, it isn’t state.


6- How can you identify where state needs to live?, our state is:

The search text the user has entered
The value of the checkbox





  :grinning:  
:grinning: