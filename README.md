# Sticky Sections Example

This project demonstrates how to create sections with headers that remain "sticky" at the top of the viewport as the user scrolls. Each section's header stays fixed until the next section's header replaces it.

## Demo

[View the live demo](https://prof-anderson-uc.github.io/sticky-sections/)

## Files Included

- `index.html`: Contains the HTML structure of the page.
- `reset.css`: Resets default browser styling to ensure consistency across different browsers.
- `sticky.css`: Contains the CSS rules that implement the sticky header functionality.

## How It Works

The sticky behavior is achieved using the CSS `position: sticky` property. This property allows an element to toggle between `relative` and `fixed` positioning, depending on the user's scroll position.

Key points:
- Each section header is assigned `position: sticky` and `top: 0`, causing it to stick to the top of the viewport when its containing section reaches the top.
- The `z-index` property ensures that the currently active header appears above others.

## References

For more information on CSS `position: sticky`, consider the following resources:
- [CSS Position Sticky - How It Really Works!](https://elad.medium.com/css-position-sticky-how-it-really-works-54cd01dc2d46)
- [How To Create a Sticky Element](https://www.w3schools.com/howto/howto_css_sticky_element.asp)

