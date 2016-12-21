# an-array-of-portuguese-words

An array of ~180,00 English words derived from internet. Works with node and browserify.

Inspired / Fork from [an-array-of-english-words])https://github.com/zeke/an-array-of-english-words)

## Programmatic Usage

To use the module in Javascript code, install it locally:

```sh
npm install an-array-of-portuguese-words --save
```

Then:

```js
var words = require("an-array-of-portuguese-words")
var funWords = words.filter(function(w) { return !!w.match(/^fun/i) })
console.log(funWords)
```

## Command Line Usage

There's a CLI that prints all words to STDOUT. Install it globally:

```sh
npm i -g an-array-of-portuguese-words
palavra | grep queijo
```
