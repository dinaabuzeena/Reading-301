 # React Docs - lists and keys 
 1- What does .map() return?
creates an array by calling a specific function on each element present in the parent array.

2- If I want to loop through an array and display each value in JSX, how do I do that in React?
list

3- Each list item needs a unique ____
key

4- What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

# The Spread Operator
1- What is the spread operator?
 in JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

2- List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments


3-Give an example of using the spread operator to combine two arrays.

const arr1 = [1,2,3]
const arr2 = [4,5,6]
const arr3 = [...arr1, ...arr2]



4-Give an example of using the spread operator to add a new item to an array.

let numberStore = [0, 1, 2];
let newNumber = 12;
numberStore = [...numberStore, newNumber];

5-Give an example of using the spread operator to combine two objects into one.
let arr1 = [0, 1, 2];
let arr2 = [3, 4, 5];

arr1 = [...arr1, ...arr2];




# vedio 
1- In the video, what is the first step that the developer does to pass functions between components?
You can pass state values to a child component as a prop


2- In your own words, what does the increment function do?
The material we've covered about arrays is unique, and you may not be sure of how to use this knowledge

3- How can you pass a method from a parent component into a child component?
 - Create a child component and put the below code inside that component.
 - Now we will import the child component to our parent component.
- Then inside your parent function create another function to run our desire event and pass the child component to return.

