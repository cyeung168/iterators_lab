# Iterators Lab

### Description

In the iterators lab we will be continuing our exploration of
iterators. We have a series of challenges that require you to use the
iterators we discussed in class. We will try to use various testing
methods to verify that your code is working.

### Phase-1

Research the following term and summarize your findings on it two to
three sentences:

* `higher-order function`

--> Higher-order functions are functions that takes another function as an argument and results in an output for a function. Higher-order functions provide a simplified model of a problem by reducing repetitive code by introducing new vocabulary or abstracting over actions and values.
---

Update this README with a description of each of the following and an
example you've created:

* `forEach`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

--> forEach: does something to each element in an array

* `map`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

--> map: builds a new a new array where each element has put through a function

* `filter`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

--> filter: builds a new array where elements have been filtered 

* `reduce`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

--> reduce: combines all an array's elements into a single value

* `some`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some)

--> some: return a true value if any of the elements in an array argument is true

* `every`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)

--> every: opposite of the some iterator, returns true value if all of the elements in an array arugment are true

Use the notes provided to help guide you explanation.

### Phase-2

* Run `npm install` from the `iterators_lab` directory.
* Looks at the tests we've written in the `test` folder. Run the tests
  with `npm test` (also from the `iterators_lab` directory). They
  should all fail.
* Get all of the tests to pass by writing the necessary code in
  `src/iterators.js`.

### Phase-3

Refactor the following code using `map` to make only one call to the `map` function versus the two below.


```
var myNumbers = [ -1, 2, -3, 4, -5, 6];

var square = function(num) {
	return num * num;
};

var sqrRoot = function(num) {
	return Math.sqrt(num);
};


var sqrNumbers = map(myNumbers, square);
var absNumbers = map(sqrNumbers, sqrRoot);
```




