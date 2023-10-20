---
title: Component Name
type: snippet
language: react
tags: [hooks, react, state]
cover: image
dateModified: 2023-10-20
---

Explain briefly what the snippet does.

- Explain briefly how the snippet works.
- Use bullet points for your snippet's explanation.
- Try to explain everything briefly but clearly.

```jsx
const ComponentName = props => {
  const [state, setState] = useState(null);
  useEffect(() => {
    setState(0);
  });
  return <div>{props}</div>;
}
```

```jsx
ReactDOM.createRoot(document.getElementById('root')).render(
  <ComponentName />
);
```
