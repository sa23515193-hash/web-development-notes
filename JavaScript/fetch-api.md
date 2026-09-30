# Fetch API

The Fetch API is used to make HTTP requests.

```javascript
async function getProducts() {
    const response = await fetch("/api/products");

    if (!response.ok) {
        throw new Error("Request failed");
    }

    return await response.json();
}
```

Common request methods:

- GET
- POST
- PUT
- PATCH
- DELETE
