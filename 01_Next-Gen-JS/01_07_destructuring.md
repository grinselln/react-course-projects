# Destructuring
Easily extract array elements or object properties and store them in variables.

Isn't that the same as spread?  No, spread takes out **all** elements and **all** properties and distributes them in a new array or object.

Destructuring allows you to take out single elements or properties.

## Array Destructuring
```js
[a, b] = ['Hello', 'Nicole'];
console.log(a); //Hello
console.log(b); //Nicole
```

## Object Destructuring
```js
{name} = {name: 'Nicole', age: 26};
console.log(name); //Nicole
console.log(age); //undefined, we're only pulling name out of the object
```

## Example
See related HTML file.