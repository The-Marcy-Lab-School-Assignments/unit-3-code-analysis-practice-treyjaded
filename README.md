# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```

**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
* What are the expected data types for each of the parameters?
* When the function is invoked, what value are provided as arguments?
* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

Your explanation here...

The parameters for the function `forEach` are `arr` and `action`. The arguments that are passed through  are the array ['a', 'b', 'c'] and `console.log`. When the function gets invoked , the arguments are passed through and the elements are iterated through the for loop, incremented one by one. EACH element of the array is then printed on the console. The data type that the argument takes is an array and a function.
