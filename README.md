JavaScript pressable keys represented as Unicode
================================================

These are useful for sending key pressed to frameworks that expect strings, for example the Webdriver or Dalek `sendKeys` method.


Usage
-----
```javascript
var keys = require('pressable');

test.sendKeys('Exterminate' + keys.enter);
```
