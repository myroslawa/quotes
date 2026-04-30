# Quotes

**A simple application which returns a singular selection from the pile of quotes.**

# Getting started

download node.js


## Usage
```js

const Quote = require('quotes');

console.log(Quote.getQuote()); // returns quote (text & author)
console.log(Quote.getQuote({ author: false }); // return quote without the author

```

- ***getQuote()*** method returns an object containing ***text*** and ***author***.

```json

 {  
    "text":"I firmly believe that all the best things on earth have been created by brave nerds.",
    "author":"Alexei Navalny"
 }
 ```
