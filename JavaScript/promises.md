# JavaScript Promises

A Promise represents the eventual result of an asynchronous operation.

```javascript
const promise = new Promise((resolve, reject) => {
    const success = true;

    if (success) {
        resolve("Operation completed");
    } else {
        reject("Operation failed");
    }
});
```

A Promise can be:

- pending
- fulfilled
- rejected
