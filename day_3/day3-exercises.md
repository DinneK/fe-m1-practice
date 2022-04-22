## Day 3: HTML and CSS

### Chapter 7 Questions: Forms

1. If you're using an input element in a form, what attribute controls the behavior of that input?
- When using an `input` element in a form the value of the type attribute controls the behavior of that input, for example `text` will allow a single line of input.

2. What element is used to create a dropdown list?
- The `select` element allows users to select answers from a dropdown list.

3. If you're using an input element to send form data to a server, what should the `type` attribute be set to?
- The `type` attribute should be set to `submit` if you want to send data to a server.

4. What element is used to group similar form items together?
- The `fieldset` element allows you to group related form items and controls together.


### Chapter 13 and 15 Questions: Boxes and Layout

1. Describe the differences between border, margin, and padding.
- Borders surround every element box, even if the border is invisible. The margin is the space outside of the border on a box, it allows you to create space between boxes. Padding is the space between the border and the content inside of a box.

2. For a CSS rule `padding: 1px 2px 5px 10px`, what sides of the content box does each pixel value correspond to?
- The rule for CSS starts with the top and moves clockwise, therefore 1px would correspond to the top, 2px corresponds to the righthand side, 5px corresponds to the bottom and 10px corresponds to the lefthand side.

3. Describe the difference between block-level and inline elements.
- Block-level elements always start on a new line and add some space before the next element. Inline elements do not start on a new line and only take the amount of width necessary for the element.

4. What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?
- Fixed positioning allows you to control where a box appears in relation to the browser window, it's great if, for example, you want the title of a page to remain at the top of the screen even while you scroll through the rest of the page. In the scenario of fixed positioning the z-index is important, because it allows you to decide which element will be on top.

5. What is the difference between a fixed and liquid layout?
- Fixed layouts are layouts in which the position of the elements don't change, this allows for more control over the design, but you can wind up with a lot of whitespace at the edge of the space. Liquid layouts are able to expand to fit the page, but this can distort the design and leave gaps between elements.

[Day 3 Practice](https://codepen.io/Dinne/pen/eYyXZjj?editors=1111)
