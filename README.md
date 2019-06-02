# Natours #

## Notes ##

- Absolute positioned elements fit to the width of their content
- Absolute positioned elements are taken out of the normal flow, parents will collapse and loose their height
- Can only use height, width, margin / padding top & bottom on block level elements
- Think about component reuse when adding padding / margins
    - Adding margin / padding for a specific context / usage makes the component less flexible in other contexts
- Use `margin: 0 auto;` to centre a block element within another block element
- Use `text-align: center;` to center inline elements