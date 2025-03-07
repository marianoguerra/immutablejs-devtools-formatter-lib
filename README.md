# immutablejs-devtools-formatter-lib

Include [immutable.js](https://immutable-js.com/) devtool formatters for Chrome and Firefox in your project, no extension required.

Original code from https://github.com/andrewdavey/immutable-devtools

## Usage

Copy the file in your project, then:

```js
import {install} from './immutable-devtools-formatter-lib.js';
import * as Immutable from 'path-to-immutable.js';

install(Immutable);
```

you can install it only on dev, or on demand.

## License

BSD 3-Clause "New" or "Revised" License, see LICENSE file
