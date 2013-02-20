Codebird.js module for Parse.com Cloud Code
===========================================

This library is a [Codebird.js](https://github.com/mynetx/codebird-js) (2.2.3) module for [Parse.com Cloud Code](https://parse.com/docs/cloud_code_guide#started). 
Codebird.js is a javascript framework to interact with Twitter OAuth API and was developed by Github user [mynetx](https://github.com/mynetx).

Installation
------------

- Place `module-codebird.js` and `module-sha1.js` in your `cloud` folder.
- In `main.js`, add the following lines:

```javascript
var Codebird = require('cloud/module-codebird');
var codebird = new Codebird();
```