# javascript-utility

A set of common JavaScript utility helper functions.

## Installation

```bash
$ yarn add javascript-utility
or
$ npm i --save javascript-utility
```

## API

### Utility functions

- `isPositiveNumericString` Returns `true` when its input is a positive numeric string and otherwise returns `false`.
- `isNumericString` Returns `true` when its input is a numeric string and `false` otherwise.
- `isEmpty` Returns `true` when its input is `null`, `undefined`, or has `length` 0.
- `isEmptyString` Returns `true` when it's input is an empty string or contains only whitespace.
- `notEmpty` Returns `true` when its input is not `null`, `undefined` or has `length` 0.
- `notNumericString` Returns `true` when its input is not a numeric string and `false` otherwise.

### Utility creators

- `lengthMoreThan` Given a number, returns a function that returns true when that input has length more than that number and false otherwise.
- `lengthLessThan` Given a number, returns a function that returns true when that input has length less than that number and false otherwise.

### Helpers

- `not` Given a function that returns a boolean, returns a function that returns a boolean in the opposite cases.