# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```

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
property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
organizing data in a way to restrict the users access
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle. a class has only one job
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
the class is like a way to format what you want the instance to be. The instance is the actual object within the class
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a proxy object is a object that acts in place of another class or function but under a specific set of rules
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
to organize your code within different files. The pro standard, useful in big projects. Also heavily useful to encapsulate
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller sets up the functions that the service enacts. the controller is what is selected by the user when they interact with the page
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
the service is like the guts of the functions. They change and manipulate data
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
model is what you want your data to be formatted as. This runs through the appstate to create your objects/arrays of data. You can also put templates here so you can dynamically change the contents with ${this.___}
```
