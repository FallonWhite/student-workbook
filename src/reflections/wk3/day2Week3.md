What is the purpose of Encapsulation?

To bundle data and the methods that act on that data such that access to that data is restricted from outside the bundle.

What were some of the problems with closures and the underscore prefix?

Privileged functions and methods have reference-based access to the containing function's variables even after the containing function has returned. Those references are live, so if the state changes in the containing function, in changes for every privileged function with access to the reference.

How do we create private variables in a ES6 Class? Why would you do this?

Everything inside an ES6 module is private by default. They remain private, so import and export are necessary to access the variables. There are many reasons why you would want your information private, but I assume one of the main reasons is to ensure that it cannot be altered, or stolen. Also, there may be proprietary info that needs to be inaccessible.

Afternoon: https://github.com/FallonWhite/VendingMachine