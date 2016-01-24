![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# JavaScript Functions - "Ins & Outs"

## Prerequisites

- [JavaScript Basics 2](https://github.com/ga-wdi-boston/js-basics-2)

## Required Reading

[JavaScript Functions - "Ins & Outs" - Study](https://github.com/ga-wdi-boston/js-functions-ins-and-outs-study#readme)

## Introduction

JavaScript function argument and return values

## Objectives

By the end of this lesson, students should be able to:

- Create and invoke functions that take an arbitrary number of arguments
- Create and invoke functions that take objects as arguments
- Create and invoke functions that return objects
- Create and invoke functions that take functions as arguments
- Create and invoke functions that return functions

## "Ins & Outs"

### "Ins"

#### Zero or more arguments

JavaScript provides a mechanism to handle arguments not in the function definition: the `arguments` object.  This object is referred to as `array like` and is available within any function.  We'll examine how this object is used by creating some seemingly parameterless functions.


##### Demo

```js
var product = function product() {

};
```

##### Code along

```js
var max = function max() {

};
```

Could we accomplish something similar using a single argument?

#### Reference types as arguments

Reference types passed as arguments can be modified within the functions.

##### Demo

```js
var aryTimes2 = function aryTimes2() {

};
```

##### Code along

```js
var addProperty = function addProperty() {

};
```

Functions are valid arguments.

```js
var transform = function transform(value, predicate, mutator) {

};
```

### "Outs"

#### Reference types as returns values

Reference type literals returned from functions create new instances of the type.

##### Demo

```js
var createArray = function createArray() {

};
```

##### Code along

```js
var mergeConfig = function mergeConfig() {

};

var createAdder = function createAdder() {

};

var createPerson = function createPerson(givenName, surname, dob, height, weight, eyeColor) {

};

```

## Additional Resources

- [Array slice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)
- [Array shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift)
- [Function call](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)

## Assessment

Please follow the instructions at https://github.com/ga-wdi-boston/js-functions-ins-and-outs-assessment
