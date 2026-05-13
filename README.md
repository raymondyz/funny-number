# is-funny-number

> Checks if an integer is a funny number.

A scientifically rigorous library for detecting funny numbers.

## Installation

```bash
npm install is-funny-number
```

## Usage

ESM:

```js
import { isFunnyNumber } from 'is-funny-number';

isFunnyNumber(6); // false  (not funny)
```

CommonJS (Node 22+):

```js
const { isFunnyNumber } = require('is-funny-number');

isFunnyNumber(6); // false (not funny)
```

## API

### `isFunnyNumber(n)`

Returns `true` if `n` is a funny number, `false` otherwise.

**Parameters**
- `n` *(number)* — an integer to check

**Returns**
- *(boolean)* — whether the number is funny

**Throws**
- `TypeError` if `n` is not an integer

## License

MIT