# HTML/CSS Cheat Sheet

### Padding/Margin/Border

Padding = increases space between edge of box and content inside
Margin = increases space between box and any others next to it
Border = adds space between margin and padding

### Block/Inline

Both display types

Block = elements stacked
Inline = elements side-by-side

### Flexbox

Create a flex container class that sets the display to flex

flex-grow = growth factor
flex-shrink = shrink factor
flex-basis = initial size of flex item

Shorthand:
flex: 1 -> grow 1, shrink 1, basis 0

Flex-direction
- row = top-bottom
- column = left-right

Put these on container:
- display: flex
- flex-direction: row/column

Puth these on items:
- flex: x

### Special flex options

justify-content: space-between
- Adds space between each item in a flex container according to the size of the screen

align-items:
- changes placement of items along the cross axis

gap:
- adds specified space between flex items, like a margin would

### Tables

declare with table
tr = table row
th = table header
td = table data