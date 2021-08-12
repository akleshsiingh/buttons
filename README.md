@akleshsiingh/buttons

[![GitHub issues](https://img.shields.io/github/issues/akleshsiingh/buttons)](https://github.com/akleshsiingh/buttons/issues)


## INSTALL

```
    npm install @akleshsiingh/buttons --save
```
## usage

```js

const removeSpace = require('@akleshsiingh/buttons');

removeSpace("Hi this is me, how are you");
//=> "Hithisisme,howareyou" 
removeSpace(1234);
//=> Uncaught TypeError: this function wants a string!
//    at buttons (<anonymous>:2:41)
//    at <anonymous>:1:1

```
