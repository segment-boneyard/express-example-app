express-example-app
==============

Set up an Express app with analytics-node

# `express express-example-app`

# `cd express-example-app`

# `npm install analytics-node`

# Add the following to your `app.js` file:
```
var Analytics = require('analytics-node');
var analytics = new Analytics('YOUR_WRITE_KEY');
```

# Replace YOUR_WRITE_KEY with the key in your project's settings. Done.