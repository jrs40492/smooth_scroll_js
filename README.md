# Smooth Scroll

A pure JavaScript smooth scroll animation for scrolling to sections of a site on button click.

This was built since the scrollIntoView method isn't fully supported in most modern browsers yet.

## Helpers

1. isOnScreen(element)

- Determines if element is fully visible (nothing cut off)
- Takes 1 parameter, a DOM element

2. isPastScreen(element)

- Determines if any part of the element has been scrolled out of view
- Takes 1 parameter, a DOM element
