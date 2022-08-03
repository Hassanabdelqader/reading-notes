## What is a ‘call’?
  Ans : invok the function
## How many ‘calls’ can happen at once?
  Ans :It is single-threaded. Meaning it can only do one thing at a time.

## What does LIFO mean?
  Ans : Last In First Out
## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
```
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```

    1- function 3 invoked 
    2- call function 
    3- call function 1

## What causes a Stack Overflow?
  Ans : A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. 
  The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.
  Here is an
  
  

## What is a ‘reference error’?
  Ans  : a variable that is not yet declared you get this type os errors.
  
## What is a ‘syntax error’?
   Ans : I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax,
## What is a ‘range error’?
   Ans : when to manipulate an object with some kind of length and give it an invalid length
## What is a ‘type error’?
   Ans : Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
## What is a breakpoint?
   Ans : it's like to stop excuting code during debugging
## What does the word ‘debugger’ do in your code?
   Ans :it lets the code has more tools to watch and fetch data and variables during excution

## Bookmark and Review
- [JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
- [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
- [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)


## Things I want to know more about 
- Call Back
