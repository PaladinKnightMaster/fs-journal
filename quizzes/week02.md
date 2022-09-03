# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var(bad) let(good) const(good)
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a set of instruction for the computer
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsiby
open closed
liskov substitution
interface segregation
dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
pineapple is in position [2] because the first object(apple) starts at position [0]
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
let you = { name:"You", hair: true, friends: [them] }
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
If statement
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
increases a value, i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
document object mode, html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
string, number, null, boolean, undefined, bigInt, symbol, nan, objects
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameter is what the function takes in when being run, and the argument is when the function is being envoked. The parameter uses whatever the value the argument has within the code when being run.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
a primitive value is a value that cant change its definition while a reference is a value that can be changed
```