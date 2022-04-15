# Passing Functions as Props

## React Docs - lists and keys
1. What does .map() return?
* map() calls a provided callbackFn function once for each element in an array, in order, and constructs a new array from the results. The function, element, index and array ae required as arguments.

For example:
```javascript

const array1 = [5,0,4,1];

// pass a function to map
const map1 = array1.map(x => x * 2);

console.log(map1);
// expected output: Array [10,0,8,2]

```

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
* You would create a function and send the JSX value (including the value) to the component you wish to use to render the results. See example below:

```javascript
//Retrieved from https://codepen.io/gaearon/pen/GjPyQM?editors=0011
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((numbers) =>
  <li>{numbers}</li>
);

ReactDOM.render(
  <ul>{listItems}</ul>,
  document.getElementById('root')
);

```

3. Each list item needs a unique _____.

4. What is the purpose of a key?
* A “key” is a special string attribute you need to include when creating lists of elements.  It helps React identify items that have changed, been added or removed. Keys should be given to the elements inside the array to give the elements a stable identity. In the example above, you code include a key using the following:

```javascript

<li key={number.toString()}>
      {number}
    </li>
```

## The Spread Operator
1. What is the spread operator?
* In React, the spread operator (...) allows us to quickly copy all or part of an existing array or object into another array or object. With objects, if there is a conflict in key/values in an object, then the last object merged will apply.

2. List 4 things that the spread operator can do.
* The spread operator can add items to arrays, combine multiple arrays, combine multiple objects, and spread an array out into a function’s arguments.

3. Give an example of using the spread operator to combine two arrays.

```javascript

const arr1=[3,8,4,6];
const arr2=[5,0,4,1];
const newArray = [...arr1, ...arr2];

//expected output [3, 8, 4, 6,5, 0, 4, 1]
console.log(newArray);

```

4. Give an example of using the spread operator to add a new item to an array.

``` javascript
const arr1=[3,8,4,6];
const newArray = [...arr1, ...[60]];

//expected output [3, 8, 4, 6,5, 0, 4, 60]
console.log(newArray);
```


5. Give an example of using the spread operator to combine two objects into one.

``` javascript
const male={
hisName: "Gene",
  age: 55,
}

const female={
herName: "Ari",
carColor: "Red"  
}

const combined={...male,...female}

//expected output { hisName: 'Gene', age: 55, herName: 'Ari', carColor: 'Red' }
console.log(combined);
```

## How to Pass Functions Between Components
1. In the video, what is the first step that the developer does to pass functions between components?

* The first thing the developer does is create a named arrow function in the parent component that recieves data for processing.

2. In your own words, what does the increment function do?
The increment function iterates over the people array and and increments the count value for the object if the person component. This occurs when the "Add" button onClick() event is clicked

3. How can you pass a method from a parent component into a child component?

* You can pass a method by binding the function to a component instance.

4. How does the child component invoke a method that was passed to it from a parent component?

* To call a function declared from a child component, ithe function must be passed to the child then called from the child component

--------------
References: [Binding Functions(https://reactjs.org/docs/faq-functions.html)

[Child calling a Method From Parent](https://stackoverflow.com/questions/37949981/call-child-method-from-parent)

[Child calling a Method From Parent (Other)](https://www.codingdeft.com/posts/react-calling-child-function-from-parent-component/)
