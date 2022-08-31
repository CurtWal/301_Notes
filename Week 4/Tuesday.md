Tuesday August 30, 2022

What is a ‘call’?
- A call is a function invoctaion/ a way to start the function


How many ‘calls’ can happen at once?
- One at a time.


What does LIFO mean?
- It stands for 'Last In, First Out' and it means that the last function that get pushed into the stack is the first to be popped out when the function is returned


Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
- functionOne = () => {
    console.log("Hello There!");
}
- functionTwo = () => {
    functionOne();
    console.log("Goodbye!");
}
- functionTwo();


What causes a Stack Overflow?
- When theres a  recursive function/ A function that endlessly calls itself


What is a ‘reference error’?
- Its an error that tells you that a variable is not defined/ declared


What is a ‘syntax error’?
- An error when you have something that cannot be parsed 


What is a ‘range error’?
- AN error when you try to manipulate an object with some kind of length and give it an invalid length


What is a ‘type error’?
- An error that occurs when trying to access a property in an undefined type of variable


What is a breakpoint?
- An intentional stopping or pausing place in the code, put in place for debugging purposes


What does the word ‘debugger’ do in your code?
- To me it means to look over code and find/fix broken code to make it run better/again.

