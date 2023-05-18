# Array Lesson

## Introduction
  <details> 
    <summary>  What is an array?  </summary>
      <br>
        <p>
        An array is a data structure consisting of a collection of elements (values or variables), each identified by at least one array index or key. Or in simpler terms an array is a way to represent lists in programming. 
        </p>
  </details>

## Lesson Overview
  #### By the End of This Lesson We Should be Able to Answer...
  * Why are arrays useful?
  * How do we create arrays?
  * What is a for loop?
  * What are array methods?

## Array Use Cases
We have a list of groceries to grab and want to use JavaScript to help us write a program to keep track of our groceries so we don't forget anything. A simple way to represent our grocery list in code could be to create a variable for every item we need.

```js

let itemOne = "apple"
let itemTwo = "peanut butter"
let itemThree = "coffee"


```

While this works fine to represent our grocery list, it isn't dynamic and it can become tedious to keep track of every item in our grocery list the longer it gets. If we have a grocery list of 10 items it is pretty easy to tell what item number 7 is but if our list is 100 items long finding item number 77 becomes a more time consuming. This is where arrays come in!

## Creating Arrays
There are two ways to create arrays in JavaScript. The first is using the array constructor method and the second is using array literal notation. Array literal notation is cleaner and much more common.

```js
// Using array constructor
let array = new array("apple", "peanut butter", "coffee");

// Using the literal notation
let array = ["apple", "peanut butter", "coffee"];

```
<details> 
 <summary> extra </summary>
  Its worth noting that if you pass a single number (N) using the array constructor method it will create an array with (N) empty values. For example...

  ```js
  // Using array constructor
  let array = new array(5);

  // This creates an array with 5 empty values that looks like this
  [ , , , , ]

  //And NOT
  [5]
  ```
</details>

## Looping Over Arrays

## Array Methods
  ### Finding Primitive Values
  ### Finding Reference Values

## References


