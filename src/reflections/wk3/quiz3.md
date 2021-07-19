# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction. Encapsulation. Inheritance. Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.property
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
A process of binding the data (i.e. variables) with the functions acting on that data. It allows us to control the data and validate it
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility Principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint which you use to create objects. An object is an instance of a class - it's a concrete 'thing' that you made using a specific class. So, 'object' and 'instance' are the same thing, but the word 'instance' indicates the relationship of an object to its class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
An object that wraps another object (target) and intercepts the fundamental operations of the target object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Divides the application into three parts that are dependent and connected to each other. Makes for cleaner code, easier debugging, and added privacy.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Where we connect everything. The role of the controller is to glue both the view and the model together while keeping their roles separated.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Takes the place of handling of data, allowing logic to be applied to several models from one place. Like a hub, an added layer to pull from.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
A Model contains the data that users work with. Responsible for handling/manipulating the data, talking to database, and returning data to the controller.
```

