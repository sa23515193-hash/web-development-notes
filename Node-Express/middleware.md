# Express Middleware

Middleware functions run during the request-response cycle.

```javascript
app.use(express.json());

function logger(req, res, next) {
    console.log(req.method, req.url);
    next();
}

app.use(logger);
```

Common middleware uses:

- Parsing JSON
- Authentication
- Logging
- Validation
- Error handling
