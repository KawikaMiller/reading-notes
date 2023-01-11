# Reading - Class 04

These notes cover how to create hyperlinks on a webpage, basic rules about positioning elements using CSS as well as introductory information about functions in JavaScript

## Learn HTML - Creating Hyperlinks

1. **To create a basic link, we wrap text or other content inside what element?** We wrap things inside of an anchor, `<a>`, element.

2. **The `href` attribute contains what information?** The `href` attribute contains the path to whatever it its we want our link to go to. Typically, it's a link to an external website but it can also be used to jump to other parts of the same website.

3. **What are some ways we can ensure links on our pages are accessibile to all readers?** By using "strong link text" which helps to indicate where the link goes. For example, instead of using "click here" you would write "about us" as the hyperlink text instead. If our hyperlink also includes an image of some kind, like an icon, we should also include the `alt` tag for our image which gives it a text description for people who use screen readers.

[Source](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)

## CSS Layout - Normal Flow & Positioning

1. **What is meant by "normal flow"?** The way that HTML elements display themselves by default if we have not changed any of their positioning properties.

2. **What are a few differences between `block-level` and `inline` elements?** `block-level` elements will be the only thing displayed on their corresponding "line". For example, if we have three boxes and they are all at `block-level` they will all appear above / below each other. Block level elements also fill any available whitespace of the parent element that holds it. With `inline` elements if we use the same example with the three boxes, they would appear side-by-side next to each other so long as they have enough room to do.

[Source for 1 & 2](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

3. **Static** positioning is the default for every HTML element.

4. **Name a few advantages to using absolute positioning of an element.** Absolute positioning ensures that an element will always be at its designated position regardless of any other elements. This is useful for things like popup boxes, menus, or UI features that can be dragged / dropped anywhere on the page

5. **What is a key difference between fixed positioning and absolute positioning?**  Absolute positioning fixed an element in place relative to its nearest positioned ancestor while fixed positioning fixes an element in place relative to the visible portion of the viewport. The only caveat to this being that if one of the fixed positioned element's ancestors is also a fixed containing block with a transform property that has a value other than `none` which might cause issues.

[Source for 3 - 5](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

## Learn JS - Functions: Reusable Blocks of Code

1. **Describe the difference between a function declaration and a function invocation** A function declaration is where & how we define what a function *does* such as its parameters, internal logic, and what the return value should be - whereas a function invocation is how we *use* a declared function. When we invoke a function, we're *calling* it and the computer is actually performing the function's logic and spitting out an actual return value.

2. **What is the difference between a parameter and an argument?** A parameter is like a variable that the function is expecting as input which we define when declaring our function. When we invoke a function, the arguments are what we pass in to the function which essentially fill in those expected parameter variables.

## Misc - 6 Reasons for Pair Programming

1. **Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey** Job Interview Readiness would definitely be beneficial because I have never had any kind of tech industry job before so getting practice in the expected behaviors that interviewers are looking for would definitely be useful. Another benefit would be learning from fellow students as I can sometimes get stubborn when I try to tackle a task and get stuck on attempting to solve the issue with whatever the first method that I came up with was, whereas having a second set of eyes to help me analyze the problem and come up with a solution would break me out of that loop.

## Things I Want to Know More About
- Is there a preferred / best practices situation when applying block-level vs. inline styling?
- Same as above but with positioning elements
