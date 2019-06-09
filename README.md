# Natours #

## Notes ##

- Absolute positioned elements fit to the width of their content
- Absolute positioned elements are taken out of the normal flow, parents will collapse and loose their height
- Can only use height, width, margin / padding top & bottom on block level elements
- Think about component reuse when adding padding / margins
    - Adding margin / padding for a specific context / usage makes the component less flexible in other contexts
- Use `margin: 0 auto;` to centre a block element within another block element
- Use `text-align: center;` to center inline elements
- Transforms are the best way to move floated elements, i.e. `transform: translateX(-3rem);`
- Flexible images for responsive web design always need a width, always without exception
- Elements can't have more than one transform property, will be overridden. You can however apply more than one transform function in a single transform property. Seen in the stories component in the Natours project.
- To animate:
    - Add `transition: properties interval` to element being animated
    - Set a `transform` for the initial state
    - Set a `transform`, `filter` etc on another state i.e. `:hover`
- Use rgba with alpha value to have a translucent background i.e. `    background-color: rgba($color-white, .6);`