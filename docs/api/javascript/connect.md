# connect( [options] )

> Connect with a listening [node](/javascript/api/node).

## Arguments

#### [options] `Object`
- *[transport](/javascript/transports/websockets-connect)* `Function` By default is [ws](https://github.com/websockets/ws) on node.js and native WebSockets on browsers.

## Returns

A new [node](/javascript/api/node) instance.


## Examples

```js
// node.js
let dop = require('dop')
let listener = dop.connect() // ws by default
```

```js
// browser
import dop from 'dop'
let listener = dop.connect() // WebSockets by default
```

If you don't want to use ES6

```html
<script src="https://unpkg.com/dop"></script>
<script>
var listener = dop.connect() // WebSockets by default
</script>
```