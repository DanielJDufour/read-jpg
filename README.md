# read-jpg
Universal JPG File Reader.  Uses read-pixels in the Browser and jpeg-js in NodeJS

# install
```bash
npm install read-jpg
```

# usage in the browser / frontend
```js
import readJPG from 'read-jpg';

const result = await readJPG({ data: arrayBuffer });
// result is { height: 200, width: 100, pixels: [r1, g1, b1, a1, r2, ...] }
```

# usage in NodeJS / backend
```js
const readJPG = require("read-jpg");

const result = await readJPG({ data: buffer });
```
