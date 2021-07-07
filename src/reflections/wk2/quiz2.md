# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var declares a varible with global scope
let declares a variable with a local scope
const declares a variable with a local scope, however it's value cannot be changed after declaration.

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a reusable set of statements to perform a task or calculate a value. Functions are one of the fundamental building blocks in JS.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single Responsibility a class should be having one and only one responsibility
O - Open / Closed classes should be open for extension but closed for modification
L - Liskov Substitution parent classes should be easily substituted with their child classes without blowing up the application
I - Interface Segregation many client specific interfaces are better than one general interface
D - Dependency Inversion classes should depend on abstraction but not on concretion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
fruit[2]. Arrays have a zero-based index so apple is 0, banana is 1, making pineapple 2.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them);
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
If, else if, else.

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The iteration. i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. HTML or xml.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Bigint, string, boolean, null, undefined, object, symbol, and function. I think that's what the question is asking for.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are variables defined by a function that receive a value. An argument is the data passed when the function is called.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are data that are stored on the stack. Primitive value is stored directly in the location that the variable accesses. Reference values are objects that are stored in the heap. Reference value stored in the variable location is a pointer to a location in memory where the object is stored.
```