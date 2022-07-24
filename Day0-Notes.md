# Alot of advantegs for props and state since we need to store data and passing data 
and of course sometime rednder our App depending on state changes.



## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
 Ans : render before componentDidMount,

## What is the very first thing to happen in the lifecycle of React?
 Ans : the constructor method


## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.
  1-constructor.
  2-render.
  3-React Updates.
  4-componentDidMount.
  5-componentWillUnmount.

 ## What does componentDidMount do?
   Ans: This method is invoked immediately after a component is mounted.
        If you need to load anything using a network request or initialize the DOM, it should go here.
        This method is a good place to set up any subscriptions.

## What types of things can you pass in the props?
 Ans : Anythings can pass through props (Ex : js type from number to object).

## What is the big difference between props and state?
 Ans : the props pass into the component but the state is handeled inside the component and can update inside the component
 and props handle oustside the components and can updated outside the Components.

## When do we re-render our application?
  Ans : if you need to change something in application or simply when the state changed or updated

## What are some examples of things that we could store in state?
  Ans : 1-counter need to be upadted  
        2-form component (checkBox,input box , selected box ) need state to store the value choosen by user.
        
       


# Additional Resources 
* [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
* [React Docs - handling events](https://reactjs.org/docs/handling-events.html)
* [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
* [React Bootstrap Documentation](https://react-bootstrap.github.io/)
* [Boootstrap Cheatsheet](https://reactjs.org/docs/components-and-props.html)
* [Bootstrap Shuffle - a class “sandbox”](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
* [Netlify](https://www.netlify.com/)
* [How to use Props in React](https://www.robinwieruch.de/react-pass-props-to-component/)


# Things I want to know more about
 State and State and state and Of course the matter here is State Managament 



