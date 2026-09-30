# Async/Await

`async` and `await` make asynchronous JavaScript easier to read.

```javascript
async function loadData() {
    try {
        const response = await fetch("/api/products");
        const data = await response.json();

        console.log(data);
    } catch (error) {
        console.error(error);
    }
}
```

Use `try/catch` for handling errors in asynchronous code.
