# Understanding Array.prototype.map()

<p>The map() method in JavaScript is used to create a new array by applying a function to each element of an existing array. The original array is not modified. It is commonly used when you want to transform or manipulate the items of an array. </p>

## Iterative methods

Many array methods take a callback function as an argument. The callback function is called sequentially and at most once for each element in the array, and the return value of the callback function is used to determine the return value of the method. They all share the same signature.

```JS
method (callbackFn, thisArg)
```
*NOTE - Where callBackFn takes three arguments:
- Element : the current element being processed
- index : The index of the current element being processed in the array
- Array : The array that the element was call upon.
  - **STUB - What callbackFn is expected to return depends on the <i> array </i> method that was called.