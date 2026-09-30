# Express Routes

Routes define how the server responds to requests.

```javascript
app.get("/api/products", getProducts);
app.post("/api/products", createProduct);
app.put("/api/products/:id", updateProduct);
app.delete("/api/products/:id", deleteProduct);
```

For larger projects, routes can be separated into modules.
