*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-constant-case](http://github.com/ianstormtaylor/to-constant-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-constant-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-constant-case

  Convert a string to a constant case.

## Installation

    $ component install ianstormtaylor/to-constant-case
    $ npm install to-constant-case

## Example

```js
var constant = require('to-constant-case');

constant('camelCase');  // "CAMEL_CASE"
constant('snake_case'); // "SNAKE_CASE"
constant('dot.case');   // "DOT_CASE"
constant('weird[case'); // "WEIRD_CASE"
```

## API

### toConstantCase(string)
  
  Returns the constant-case variant of a `string`.

## License

  MIT
