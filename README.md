# Kitty System Base
## Over
Kitty System Based Manager is a comprehensive utility module designed to simplify and enhance JavaScript development. 

It provides a wide range of utility functions to perform common tasks such as type checking, value comparison, and network request handling. This module is particularly useful for developers looking to streamline their code and improve its readability and maintainability.


## Features
Type Checking: A variety of functions to check the type of a given value, including isType, isNull, isUndefined, isArray, isFunction, isObject, isString, isNumber, isBoolean, isNaN, isInfinity, isNullOrUndefined, isSymbol, isBigInt, isRegExp, isDate, and isError.

Value Comparison: Functions to compare values, such as isValueMatch and isInArray.

Object and Array Utilities: Utilities to check if an object is empty (isEmptyObject), an array is empty (isEmptyArray), or if a value is a property of an object (isPropertyOfObject) or a method of an object (isMethodOfObject).

Network Request Handling: Functions to test network requests (nres and ts200) and to throw custom errors (sErr).

## Installation
To install Kitty System Based Manager, use npm:

```
npm install kitty_base
```
## Usage
To use Kitty System Based Manager in your project, simply import it:

```
const kitty = require('kitty_base');
```
Then, you can use any of the utility functions provided by the module. For example, to check if a value is a string:

```
const isString = kitty.isString('Hello, world!');
console.log(isString); // true
```
## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests.

## License
Kitty System Based Manager is licensed under the MIT License. See the LICENSE file for more details.