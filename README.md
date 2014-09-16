express-example-app
==============

Set up an Express app with analytics-node

1. `express express-example-app`

2. `cd express-example-app`

3. `npm install analytics-node`

4. Add the following to your `app.js` file:
```
var Analytics = require('analytics-node');
var analytics = new Analytics('YOUR_WRITE_KEY');
```

5. Replace YOUR_WRITE_KEY with the key in your project's settings. Done.