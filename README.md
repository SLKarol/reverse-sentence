# reverse-sentence

Переворачивает слова предложения.

## Install

```sh
npm install @stanislavkarol/reverse-sentence
```

## API

```js
require('reverse') => Function
reverse(sentence) => String
```

## Example

```js
const reverseSentence = require("reverse-sentence");

const sentence = "Hello Beth!";

const reversed = reverseSentence(sentence);

console.log(reversed); // Beth! Hello
```

## License

MIT
