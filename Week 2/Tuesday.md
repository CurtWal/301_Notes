Tuesday August 16, 2022

What is the single responsibility principle and how does it apply to components?
- that a component should only do one thing only and if it do grow into doing more then one thing it should be decomposed into smaller subcomponents.


What does it mean to build a ‘static’ version of your application?
- To build an application that renders the UI and data, but no interactivity


Once you have a static application, what do you need to add?
- add interactivity to the application


What are the three questions you can ask to determine if something is state?
- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in
your component? If so, it isn’t state.


How can you identify where state needs to live?
- Where all the data needs to be pulled from and passed down to the subcomponents.


What is a “higher-order function”?
- They are functions that operate on other functions, either by taking them as arguments or by returning them


Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
- It returns the function when checking if the numbers the user enters is greater then the argument.

Explain how either map or reduce operates, with regards to higher-order functions.
- map is a method that transforms an array  by applying a function to all of its elements and build a new array from the returned values
