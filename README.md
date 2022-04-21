# Gradient border using Pseudo Elements

- Because the border-image attribute doesn't work with border radius
- Place the pseudo element with absolute positioning

### Steps

- On the main element, set the gradient background

- On the pseudo element,

```
    width: calc(100% - 10px);
    height: calc(100% - 10px);
```

is equivalent to

```
    border: 5px solid gradient()
```

- use inset: 5px to center the pseudo element
