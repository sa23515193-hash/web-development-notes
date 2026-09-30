# React useEffect

`useEffect` is used for side effects such as fetching data, subscriptions, or interacting with browser APIs.

```jsx
import { useEffect } from "react";

useEffect(() => {
    console.log("Component effect ran");
}, []);
```

An empty dependency array generally means the effect runs after the initial render.
