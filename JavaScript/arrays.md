# JavaScript Arrays

Arrays store ordered collections.

```javascript
const skills = ["HTML", "CSS", "JavaScript"];
```

Useful methods:

```javascript
skills.push("React");
skills.pop();

const upper = skills.map(skill => skill.toUpperCase());
const filtered = skills.filter(skill => skill.length > 4);
```

Important methods include:

- `map()`
- `filter()`
- `find()`
- `reduce()`
- `forEach()`
- `includes()`
