## What does .map() return? 
 Ans :map() function to take an array and return new Array after we do some manpulation.



## If I want to loop through an array and display each value in JSX, how do I do that in React?
 Ans : Actucally there is many way but the best one 
- using Map function 
- assign a html tag for the iterated array and wen can use the value between {}

## Each list item needs a unique Key
 Ans : Key


## What is the purpose of a key? 
Ans : Keys help React identify which items have changed, are added, or are removed


 ## What is the spread operator?
   Ans: it is and Js Object mainly used to expand the any Itrable obejct 
  (String , Array , ect ) to the list of arguamnnet .

## List 4 things that the spread operator can do.
 Ans : 
   1- copy the arra.
   2- compain arrays. 
   3- Adding to state in React.
   4- Converting NodeList to an array.


## Give an example of using the spread operator to combine two arrays.
 Ans : 
  ```
      const arr1 = [1,2,3];
      const arr2 = [4,5,6];
      const arr3 = [...arr1,...arr2];

```

## Give an example of using the spread operator to add a new item to an array.
Ans :
    ```
    const Num = [1,2,3,4]
    const Num2 = [4,5,6, ...Num]
    ```

## Give an example of using the spread operator to combine two objects into one.
  Ans : 
    ```
    const obj1 = [name: 'Hasan'];
    const obj2 = [age, 25];
    const objCombined = [...obj1,...obj2];
    ```
    
## In the video, what is the first step that the developer does to pass functions between components? [Video](https://www.youtube.com/watch?v=c05OL7XbwXU)
 Ans after creaeing the function he assign the functionto value using : increament ={this.increament}

## In your own words, what does the increment function do? 
 Ans : increamnt the counter +1 and set state to update the counter and rerender 
 
 
## How can you pass a method from a parent component into a child component? 
 Ans : 
 - A parent component defines a function
 - The function is passed as a prop to a child component
 - The child component then invokes the prop
 - The parent function is then called, usually changing something
 - Then the parent component is re-rendered along with its children
  
  
## How does the child component invoke a method that was passed to it from a parent component?
Ans : using the this . props . the method   

# Additional Resources 
* [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
* [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)


# Things I want to know more about
 passing function between component


