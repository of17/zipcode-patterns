# zipcode-patterns

> A list of regular expressions for zip codes


## Install

```sh
$ npm install --save zipcode-patterns
```


## Usage

via require:

```js
const zipcodes = require('zipcode-patterns');

console.log(zipcodes)
// => "AC": "^(ASCN 1ZZ)$", "AD": "^(?:AD)*(\\d{3})$", etc

const deZipPattern = new RegExp(zipCodes['DE']);
const isValid = deZipPattern.test('89081');

```

via import:

```js
import * as zipCodes from 'zipcode-patterns/zipcode-patterns.json';

const deZipPattern = new RegExp(zipCodes['DE']);
const isValid = deZipPattern.test('89081');
```

## License

MIT © [Henrique Dias](http://henriquedias.com)
