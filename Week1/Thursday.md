Thrusday August 11, 2022

What does .map() return?
- It returns a map object(an iterator)


If I want to loop through an array and display each value in JSX, how do I do that in React?
- nameoftheArray.map((parameter) into a funtction => )


Each list item needs a unique ____.
- string


What is the purpose of a key?
- It helps React identify which item have changed, are added, or are removed


What is the spread operator?
- It is used to expand an iterable object into a list of arugments


List 4 things that the spread operator can do.
- Adding an item to a list
- Combining Objects
- Converting NodeList to an array
- Using an array as arguments

Give an example of using the spread operator to combine two arrays.
- const add = ["This","And"] const together = ["that"] const addTogether = [...add, ...together] console.log(addTogether)


Give an example of using the spread operator to add a new item to an array.
- const alone = ['alone'] const notAnymore = ['joined', ...alone] console.log(notAnymore)


Give an example of using the spread operator to combine two objects into one.
- const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree)


In the video, what is the first step that the developer does to pass functions between components?
- give it some state to pull from


In your own words, what does the increment function do?
- It changed the value rather it be postive or negative


How can you pass a method from a parent component into a child component?
- this.state


How does the child component invoke a method that was passed to it from a parent component?
-  It uses this.props.methodCallName()

## Things I want to know more about