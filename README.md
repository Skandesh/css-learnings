css learnings:

## Boilerplate:

- CSS resetting and setting `w` and `h` properties to 100% - done to ensure a consistent behavior across different browsers.

```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }

html,
body {
width: 100%;
height: 100%;
}

```

## Commonly used properties:

- `display: flex` - to display the child elements aside, to prevent default positioning (one below other).

  - `align-items ` - to align flex elements vertically/cross axis of current line of flex element.
  - `justify-content` - to align flex elements along/main axis the current line of flex element.

- `gap` - the gap between elements.
- `z-index` - to specify the priority of the items. 9999 is the top most priority, can be used only with absolute positioning, relative positioning, flex and grid positioning.

- `white-space:nowrap` - to display text without breaking the line.

- `user-select: none` - to disable user interaction.
- `user-select: all` - to automatically select all whie clicking the element`

@@TODO:

- `overflow: hidden`

- `transform-origin: 10% 50%;`
- `transform: rotate(270deg);`
