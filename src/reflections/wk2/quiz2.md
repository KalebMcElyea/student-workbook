# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

```
There's var, let, and const.

```


**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
It's a block of code that is made for certain task
```


**3.** What are the `SOLID` principles?

```
Single responsibility 
Open-Closed
Liskov
Interface Segregation
Dependency Inversion
```


**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?

```
The pineapple is in the 2nd position because arrays are zero based. Meaning the apple = 0 
banana = 1 and pineapple = 2 etc, etc.
```


**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push("Them", false)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(3>1 == true){
  console.log("True")
}
else if(3>=3 == true){
  console.log("true")
}
else{
  console.log("false")
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
This is the incrementer. You would put i++; to increment
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. The file first accessed is the HTML file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Undefined 
Boolean
Number
String
BigInt
Symbol
Object
Function
Null
```


**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is a placeholder that defines a function and an argument is the value the function receives 
```


**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitives are datas the include the following: strings, boolean, undefined, null, numbers, symbol. References are arrays, functions, and objects.
```