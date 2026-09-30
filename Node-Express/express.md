# Express.js

Express simplifies routing, middleware, request handling, and API development.

```javascript
const express = require("express");

const app = express();

app.use(express.json());

app.get("/api/hello", (req, res) => {
    res.json({ message: "Hello" });
});
```
