# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var , constant
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```It is a task or a set of a instructions for javascript to do

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single line responsibility
open closed principle
liskov substitution principle
interface segragation principle
dependecy inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index position 2
arrays starting counting at 0 for the first item in the array

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
 you.push(them.name)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
  if (10 > 8) {
       console.log("10 is greater")
  }
   else console.log("10 is less"  )

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```It would be the increment or modifier you want the loop to do on each loop
i++

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
document object model
the index.html file

```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
null, undefined, boolean, number , string, object
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```a parameter is set into a function when you're creating it function apple("x") so x would be the paramter. The argument is then passed into the paramter "x = 5" so 5 would be the value of the parameter from the argument.

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
a primitive includes undefined, null, boolean, numbers and strings.
a reference value will include objects.
```