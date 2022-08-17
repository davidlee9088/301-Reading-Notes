## Reading Notes 03

1. What does .map() return?
.map means creating a new Array.
2. If I want to loop through an array and display each value in JSX, how do I do that in React? 
You if you want to loop through an array and display each value in JSX, first you would use {number} and you would assign resulting array of elements. 
Example : x = [],
listItems = numbers.map((x)) => <.li>number<.li/>
3. Each list item needs a unique key
4. What is the purpose of a key?
React to identify which items have changed, are added and removed.

1. What is the spread operator?
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
2. List 4 things that the spread operator can do.
Copying array, Combine Arrays, Using math functions, Using array as arguments
3. Give an example of using the spread operator to combine two arrays.
<!-- ...myArray,...yourArray -->
4. Give an example of using the spread operator to add a new item to an array.
['x(new item)', ...y(already exisiting array)];
5. Give an example of using the spread operator to combine two objects into one.
<!-- .let x = [...obj1,...obj2] -->


1. In the video, what is the first step that the developer does to pass functions between components?
He creates a function that he needs to the most parental componement. 
2. In your own words, what does the increment function do?
calls the increment function from the parent and change the count while changing the state of the parent increment.
3. How can you pass a method from a parent component into a child component?
Using the props, you can pass a method from parent to the child
4. How does the child component invoke a method that was passed to it from a parent component?
using the props method will invoke it from child.