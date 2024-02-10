# Intro to JSON

## What is JSON?
JSON (Javascript Object Notation) is a lightweight data interchange format. It uses key-value pairs and is similar to object literals in JavaScript.

The basic syntax consists of curly braces {}

for objects and square brackets [] for arrays.

## Create JSON Objects/Arrays 
You can create JSON objects and arrays in JavaScript using their respective literal syntax.

```js
// JSON Object
const person = {
    name: "Sujon Ahmed",
    age: 24,
    email: "sujonahmed5284@gmail.com"
};

// JSON Array
const fruits = ["Apple", "Banana", "Orange", "Mango"];
```

## Parse JSON
To convert a JSON string into a Javascript object, you can use JSON.parse().

```js
const jsonString = '{"name": "Sujon Ahmed", "age": 24}';

const person = JSON.parse(jsonString);

console.log(person.name); // Output: Sujon Ahmed
```

## Stringify JS objects to JSON
To convert a JavaScript Object into a JSON string, you can use JSON.stringify().

```js
const person = {
    name: "Sujon Ahmed"
    age: 24
};

const jsonString = JSON.stringify(person);

console.log(jsonString);
// Output: '{"name": "Sujon Ahmed", "age": 24}'
```