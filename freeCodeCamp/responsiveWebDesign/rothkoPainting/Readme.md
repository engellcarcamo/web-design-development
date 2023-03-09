# Learn the CSS Box Model 'Rothko Painting'

Every HTML element is its own box – with its own spacing and a border. This is called the Box Model.

Everything in CSS has a box around it, and understanding these boxes is key to being able to create more complex layouts with CSS, or to align items with other items.

## Block and inline boxes

In CSS we have several types of boxes that generally fit into the categories of block boxes and inline boxes.

- The block box occupies the entire width of the page; placing one on top of the other html element

- The inline box does not take up the entire width of the page, just its own content from the html element; placing the html element next to each other. The width and height properties will not apply.

### Parts of a box

- Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
- Padding box: The padding sits around the content as white space; size it using padding and related properties.
- Border box: The border box wraps the content and any padding; size it using border and related properties.
- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and
  other elements; size it using margin and related properties.

![BOX MODEL](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model/box-model.png)
