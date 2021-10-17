# About
In this crash course 'Traversy Media' will go over the fundamentals of JavaScript including more modern syntax like classes, arrow functions, etc.

# What is Javascript?
```
- Not related to java
- High level (a lot of abstraction - no memory management like in c/c++) interpreted (program is executed without running through a compiler - js is a scripting language) programming Language
- Confirms to ECMAScript specification ( commonly referred interchangeably as JS)
- Multi-paradigm ( code can be written in different ways - OOP / Functional ways etc. )
- Language of the browser
= Runs on the client/browser (frontend) as well as on the server (backend using Node.js - javascript runtime)
```

# Why Learn Javascript?
```
- Language of the browser ( for client side programming js is a must! python/php is server side)
- Build interactive user interfaces with frameworks like Angular/React etc
- Build fast server side / full stack applications
- Build / Develop apps for mobile (React Native, NativeScript, IONIC) / Desktops (Electron JS)
```

# [Crash Course](https://youtu.be/hdI2bqOjy3c)

# [Play Environment](https://embed.plnkr.co/plunk/8ujYdL1BxZftGoS4Cf14)

## [MDN-Best documentation for JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Variables
```
 - var : Variable (usually a globally / locally scoped definition; older way for declaration)
 These were introduced in ES6+. These are block-scoped! 
 - let : (can be changed or reassigned; can be declared without assignments)
 - const : constant (cannot be changed); used to reduce errors ; const has to be initialized at declaration
 ```

 ## Primitive Data Types
 ```
 typeof: 

-string : enclosed in '' or ""
 - 
- Boolean: true or false without '' / " "
- number : merely a number (integer or float or decimal)
- null (bogus type of object)
- undefined ( usually this is the type for let declarations without assignment)

```

## Arrays
```
Variables that hold multiple values - that can be of different data types (flexibility of js)

<!-- construction array -->
const numbers= new Array(1,2,3,4,5);

<!-- commonly used arrays -->
const fruits = ['apples', 'oranges'];

<!-- to access a specific entry -->
Since arrays are 0 based: 
console.log(fruits[1]) will return oranges

<!-- appending to the end of an array-->
fruits.push('peaches'); 

<!-- append to the start -->
fruits.unshift('mango');

<!-- remove the last from the array -->
fruits.pop()'; 
<!-- this will remove peaches form the array const fruits = ['apples', 'oranges', 'peaches']; -->

<!-- check if var is an array! -->
console.log(Array.isArray(fruits)); returns true
console.log(Array.isArray("fruits")); returns false

<!-- find the index of an item in an array -->
console.log(fruits.indexOf('oranges')); returns 1 if const fruits = ['apples', 'oranges', 'peaches']; ;
```


## Array Split
<!-- every letter in the word is split up -->
console.log(var name.split(''));
<!-- comma separated words -->
console.log(var name.split(', '));