# Learn CSS Flexbox by Building a Photo Gallery

Flexbox helps you design your webpage so that it looks good on any screen size.

- Flexbox is a one-dimensional CSS layout that can control the way items are spaced out and aligned within a container.

- Flexbox has a main and cross axis. The main axis is defined by the **flex-direction** property, which has four possible values:
  * row(default): horizontal axis with flex items from left to right.
  * row-reverse: horizontal axis with flex items from right to left.
  * column: vertical axis with flex items from top to bottom.
  * column-reverse: vertical axis with items from bottom to top.


- The **flex-wrap** property determines how your flex items behave when the flex container is too small. Has two values:
   * nowrap (default): will prevent your items from wrapping and shrink them if needed.
   * wrap: will allow elements to wrap to the next row or column.

- The **justify-content** property determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them. values: 
   - flex-start, flex-end, center, space-between, space-around, space-evenly.

- The **align-items** property positions the flex content along the cross axis. In this case, with your flex-direction set to row, your cross axis would be vertical. values:
   - Stretch, flex-start, flex-end, center, baseline. 


- The **gap** CSS shorthand property sets the gaps, also knowns as gutters, between rows and columns. The gap property and its row-gap and column-gap sub-properties provide this functionality for flex, grid, and multi-column layout. You apply the property to the container element.
