# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace is used for organizing many classes to handle the application easily.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are of reference types. Structs are of value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
I don't understand the question. The class would be abstract, but I'm not sure about the method other than return. Interface isn't refered to as a method, and I can't find anything difinitive in the Foundations of C# in the reading material.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
virtual
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
reference type data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It decouples so that flexibility is allowed. 
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual method is a method that can be redefined in derived classes, again allowing more flaxibility
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Private, protected, public, and internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed by the code in the same class or structure.
```