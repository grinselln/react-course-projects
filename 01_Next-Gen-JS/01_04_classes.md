# Classes
Consists of properties and methods
```js
class Person{
    name = 'Nicole'     /*property*/
    call = () => {...}  /*method*/
}
```

## Instantiate a Class
```js
const myPerson = new Person();

myPerson.call();

console.log(myPerson.name)
```

## Inheritance
Take the properties and methods from an existing class and potentially add additional ones.
```js
class Person extends Master
```

## Example
See the related html file.