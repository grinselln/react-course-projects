# Spread & Rest Operators
The operator is '...'.  The name depends on where it is being used.

## Spread
Used to split up array elements or object properties (spread up).

Pulls out all elements, and put it within the new array.  We can also continue to add new elements.

Pulls out all properties, and add them as key value pairs to the new object.  We can also continue to add new elements.  Our own properties take priority, our 'newProp' value in 'oldObject' would be the value given when 'newProp' is accessed.
```js
const newArray = [...oldArray, 1, 2];
const newObject = {...oldObject, newProp: 5};
```

## Rest
Used to merge a list of function arguments into an array.

Our function recieves an unlimited amount of arguments.  All will be merged together in an array 'args'.
```js
function sortArgs(...args){
    return args.sort();
}
```

## Example
See related HTML file.