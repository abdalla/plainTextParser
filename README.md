# Plain/Text Parser
Middleware for express to accept plain text on posts

### Installation
To install the stable version:
```
npm install plaintextparser --save
```

### How to use
On your server file add the plainTextParser as a Express Middleware as below.

Import plainTextParser

```
let plainTextParser = require('plainTextParser');
```

```
app.use(plainTextParser());
```
OR
```
app.post(YOUR_ROUTE, plainTextParser, function(req, res) {             
   //DO SOMETHING....
});
```
