
## What is a ‘Controlled Component’?
typically Controlled Components maintain their own state and update it based on user input

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
we should update the state with  the user's responce when they submit the form to prevent our react app from crashing because otherwise the app will re-render with each input


## How do we target what the user is entering if we have an event handler on an input field?
 this.setState({value: event.target.value} inside the event handler 
  this.state.value for targeting current value


## Why would we use a ternary operator?
to Shorten the condition into one line of code with the conditional operator
## Rewrite the following statement using a ternary statement:

    ```
         x===y ? console.log(true) : console.log(false)
    ```

## Bookmark and Review
- [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
- [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about
- about form
