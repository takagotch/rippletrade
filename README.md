### rippletrade
---
https://rippletrade.com/

```js
// coldwallet
var rippleLib = require('ripple-lib');
var wallet = rippleLib.Wallet;
var w = wallet.generate();
console.log(w)


```

```sh
// REST-API
https://api.ripple.com/v1/wallet/new

```

```json
// result
{
  address: 'xxx',
  secret: 'xxx'
}
```


