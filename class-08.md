# Reading - Class 08

These notes will cover CSS Flexbox

## Learn CSS - Flexbox

1. **Flexbox is designed for one-dimensional content. Explain what this means:** This means that content within a flexbox will automatically alter their dimensions / size in order to best fit the flexbox container which is especially helpful when some flexbox items within a flex container might have varying sizes.

2. **Explain the difference between the main axis and the cross axis:** The main axis depends on which direction the flex items are flowing via the `flex-direction` property. If flex items are being displayed in a `row` then the main-axis is the horizontal-axis / x-axis and if flex items are being displayed in a `column` then the main-axis is the vertical-axis / y-axis. The cross axis is whatever axis is opposite to the main axis.

3. **How can using certain properties of a flexbox negatively impact accessibility?** We have the option to use `row-reverse` or `column-reverse` as the value of the `flex-direction` property. When we do this the flex items are rendered in reverse order. However, when someone uses a screen reader the elements will be read in the order that they appear in the DOM. If a person is using keyboard navigation then they will also traverse these elements in the order that the appear in the DOM. This causes a disconnect between what is rendered on the screen and how the content is actually structured in the DOM which can cause issues in regard to accessibility.

## CSS Layout - Flexbox

1. **What are some advantages of using flexbox over float?** When we use flexboxes we are able to more easily center child items vertically inside of their parent elements as well as making all children of a container take up an equal amount of the available width and/or height, regardless of how much space is actually available.

2. ** How does this topic connect with your long term goals?** This topic connects with my long term goals because being able to use flexboxes will enable me to create more interesting and dynamic webpages &/o applications layouts which can then also be adapted to fit any size screen - like a phone, tablet, or desktop.

## Things I Want To Know More About
- n/a