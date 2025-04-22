---
tags: type/zettel, 
aliases: 
created: 2025-04-20 00:13:26
---
# Do not use React's `useState` hook when there's no UI update

Sometimes we use `useState` to store a value we need in our component but this value isn't rendered on the UI, just used internally. This is bad practice because on each time the value changes the component has to re-render even thought there's no UI change. Here's an example showing it:

```typescript
function BadComponent() {
  const [counter, setCounter] = useState(0);

  const increment = () => {
    setCounter(prev => prev+1);
  }

  return <button onClick={increment}>Increment</button>
}
```

On the code above, we store `counter` inside of a state, now each time a user click the increment button the component rerenders. This is a more improved version of the component using `useRef`:

```typescript
function BadComponent() {
  const counter = useRef(0);

  const increment = () => {
    counter.current += 1;
  }

  return <button onClick={increment}>Increment</button>
}
```

This now uses `useRef` which hold a value of the counter and mutating it doesn't trigger a re-render at all.

## Connections
