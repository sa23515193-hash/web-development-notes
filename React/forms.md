# React Forms

Controlled inputs keep form values in React state.

```jsx
import { useState } from "react";

function LoginForm() {
    const [email, setEmail] = useState("");

    return (
        <input
            type="email"
            value={email}
            onChange={(e) => setEmail(e.target.value)}
        />
    );
}
```
