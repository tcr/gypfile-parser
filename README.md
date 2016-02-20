# gypfile-parser

Parses most .gyp files published on npm.

What's not supported?

- The `*` operator.
- Boolean operators like `and` and `or`.
- Invalid .gyp files.

```js
var parseGyp = require('gypfile-parser').parse;

var struct = parseGyp(input);
```

## license

MIT
