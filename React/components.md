# React Components

Components are reusable pieces of UI.

```jsx
function ProductCard({ name, price }) {
    return (
        <article>
            <h2>{name}</h2>
            <p>Price: {price}</p>
        </article>
    );
}
```

Keep components focused and reusable.
