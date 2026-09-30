# Node.js and Express Notes

## Node.js

Node.js allows JavaScript to run outside the browser.

## Express.js

Express is a Node.js web framework commonly used to build backend applications and APIs.

## Basic Server

```javascript
const express = require("express");

const app = express();

app.use(express.json());

app.get("/", (req, res) => {
    res.json({ message: "API is running" });
});

app.listen(5000, () => {
    console.log("Server running on port 5000");
});
```

## HTTP Methods

| Method | Purpose |
|---|---|
| GET | Retrieve data |
| POST | Create data |
| PUT | Replace/update data |
| PATCH | Partially update data |
| DELETE | Delete data |
