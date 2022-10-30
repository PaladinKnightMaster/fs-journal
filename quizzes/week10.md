# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace is used to declare what kind of file your using so that your project is more organized
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are a lighter form of classes in that they generally hold values but classes can hold values as well as logic
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
a method that retuns an instance but withould a type is the 'Void' method
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
Public, this gives no restrictions on what can access this virtual
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
This represents what the return value's type is.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
the abstract can be used to indicate that the class isnt fully coded or functional, This might be more useful when your trying to extract the class to another with finished logic.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The 'virtual' keyword gives other classes to modify the information or logic within the virtual method
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Protected and Internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only the logic within the class or method. I believe a private methods or classes are locally scoped so that means its contents can only be access locally
```