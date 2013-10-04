node-string-substitute
======================

Simple string util which substitutes {n} tokens within the specified string

###Usage###
```javascript
var substitute = require('string-substitute');
var address = substitute('{0}, my name is {1}', 'Hello', 'Bruce Wayne');
console.log(address); //Hello, my name is Bruce Wayne
```


###Install###
```bash
npm install string-substitute
```


###Test###
```bash
mocha test
```
