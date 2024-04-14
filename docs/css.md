## Documentation

Use tab to cycle placeholders.

| Trigger | Describe           |
| ------: | ------------------ |
| `cac →` | `css.align.center` |
| `clf →` | `css.layout.flex`  |
| `clg →` | `css.layout.grid`  |
| `cr  →` | `css.reset`        |

## Snippets

### `css.align.center` | cac

```css
 {
  display: flex;
  align-items: center;
  justify-content: center;
}
```

### `css.layout.flex` | clf

```css
 {
    display: flex;
    align-items: ${[start, center, end, stretch, baseline]};
    justify-content: ${[start, center, end, space-around, space-evenly, space-between]};
    flex-wrap: wrap;
    gap: ${5:value};
}
```

### `css.layout.grid` | clg

```css
 {
  display: grid;
  grid-template-columns: repeat(
    auto-${[fill,
    fit]},
    minmax(${2: min}, ${3: max})
  );
  grid-auto-rows: $ {
    4: value;
  }
  gap: $ {
    5: value;
  }
}
```

### `css.reset` | cr

Based on [A Modern CSS Reset by Josh W. Comeau](https://www.joshwcomeau.com/css/custom-css-reset/#the-css-reset-1)

```css
*, *::before, *::after {
    box-sizing: border-box;
  }
 
  * {
    margin: 0;
  }
 
  body {
    line-height: 1.5;
    -webkit-font-smoothing: antialiased;
  }
  
  img, picture, video, canvas, svg {
    display: block;
    max-width: 100%;
  }
  
  input, button, textarea, select {
    font: inherit;
  }
  
  p, h1, h2, h3, h4, h5, h6 {
    overflow-wrap: break-word;
  }
  
  #root, #__next {
    isolation: isolate;
  }
```
