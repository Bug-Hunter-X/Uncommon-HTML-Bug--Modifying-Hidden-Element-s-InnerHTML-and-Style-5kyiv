# Uncommon HTML Bug: Modifying Hidden Element's InnerHTML and Style

This repository demonstrates an uncommon bug related to modifying the `innerHTML` and `style` of a hidden HTML element.  The bug occurs when attempting to change the content and styling of an element that has its `display` property set to `none` before the modifications are made.  This can result in unexpected behavior or no visual changes at all.

The `bug.html` file showcases the bug, and the `bugSolution.html` file provides a solution.

## Bug Description
Attempting to change the innerHTML and style of an element after setting its display property to 'none' may lead to the browser ignoring these changes, meaning the modifications won't be reflected when the element's visibility is later restored.