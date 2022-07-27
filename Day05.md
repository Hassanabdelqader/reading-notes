
## What is the single responsibility principle and how does it apply to components?
  Ans : it is a teqnick that the Fucntion or Component should do only one thing and in case we need to add more functionality or Expand te function we should 
        decomposed it into subComponent

## What does it mean to build a ‘static’ version of your application?
  Ans : this is mean to build the Component that take the data model and render it to the Ui

## Once you have a static application, what do you need to add?
 Ans : Identify The Minimal Representation Of UI State
 
## What are the three questions you can ask to determine if something is state?
   Ans :  1- If the data was driven from the parent so no state  
          2- if the data is static and never change so no State 
          3- if we can get the data from other state or other props so it is not state 

## How can you identify where state needs to live? 
   Ans : 
          Identify every component that renders something based on that state.
          Find a common owner component (a single component above all the components that need the state in the hierarchy).
          Either the common owner or another component higher up in the hierarchy should own the state.
          If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## What is a “higher-order function”? 
   Ans : Functions that operate on other functions, either by taking them as arguments or by returning them.

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
   Ans : the Function Greater here is did return a Function and this function returned 
          we used it to check if the 11 > greater than 10 
          
## Explain how either map or reduce operates, with regards to higher-order functions.
   Ans : The map method transforms an array by applying a function to all of its elements and building a new array from the returned values.
   The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.
    The reduce, apart from the array, a combining function and a start value.

## Bookmark and Review
- [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Higher-Order Functions ](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

## Things I want to know more about
- Higher Order Function
