# Hide Titlebar Buttons

Hide titlebar buttons (maximize, minimize, close).

## Installation

Copy the content of `hide-titlebar-buttons.css` into your Stremio custom theme section.

## CSS

```css
.title-bar {
    display: none !important;
    height: 0 !important;
    z-index: 0 !important;
    background: transparent !important;
    backdrop-filter: none !important;
}

html body #app {
    padding: 0 !important;
}
```
