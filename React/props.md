# React Props

Props allow a parent component to pass data to a child component.

```jsx
function User({ name }) {
    return <h2>Hello {name}</h2>;
}

function App() {
    return <User name="Sawaira" />;
}
```

Props should be treated as read-only by the receiving component.
