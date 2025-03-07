# immutablejs-devtools-formatter-lib

Include [immutable.js](https://immutable-js.com/) devtool formatters for [Chrome](https://docs.google.com/document/d/1FTascZXT9cxfetuPRT2eXPQKXui4nWFivUnS_335T3U/preview?tab=t.0#heading=h.xuvxhsd2bp05) and [Firefox](https://fxdx.dev/firefox-devtools-custom-object-formatters/) in your project, **no extension required**.

Original code from https://github.com/andrewdavey/immutable-devtools

## Usage

Copy the file in your project, then:

```js
import {install} from './immutable-devtools-formatter-lib.js';
import * as Immutable from 'path-to-immutable.js';

install(Immutable);
```

you can install it only on dev, or on demand.

Don't forget to enable the custom formatter option in devtool settings and restarting your browser.

## License

BSD 3-Clause "New" or "Revised" License, see LICENSE file
