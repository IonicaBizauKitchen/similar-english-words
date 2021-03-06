# similar-english-words

Give me a word and I'll give you an array of words that differ by a single letter.

A thing to make [levenmorpher](https://www.npmjs.com/package/levenmorpher) faster.

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install similar-english-words --save
```

## Usage

```js
const words = require("similar-english-words")

words.funky
// [ 'flunky',
//   'fundy',
//   'funk',
//   'funks',
//   'funny',
//   'gunky',
//   'hunky',
//   'junky',
//   'punky' ]

> words.blank
// [ 'bank',
//   'black',
//   'bland',
//   'blanks',
//   'blink',
//   'blunk',
//   'brank',
//   'clank',
//   'flank',
//   'lank',
//   'plank',
//   'slank' ]

words.not_a_word
// undefined

```

## Tests

```sh
npm install
npm test
```

## Dependencies

None

## Dev Dependencies

- [an-array-of-english-words](https://github.com/zeke/an-array-of-english-words): An array of ~275,000 English words. Works with node, iojs, and browserify.
- [code](https://github.com/hapijs/code): assertion library
- [leven](https://github.com/sindresorhus/leven): Measure the difference between two strings using the fastest JS implementation of the Levenshtein distance algorithm
- [lodash.compact](https://github.com/lodash/lodash): The modern build of lodash’s `_.compact` as a module.
- [mocha](https://github.com/mochajs/mocha): simple, flexible, fun test framework
- [standard](https://github.com/feross/standard): JavaScript Standard Style

## License

ISC

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_
