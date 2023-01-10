# Reading - Class 03

These notes will cover HTML lists, the Box Model, and Arrays, Conditionals, Loops, and Operators & Expressions.

## HTML - Ordered & Unordered Lists

1. **When should you use an `unordered list` in your HTML documents?** When the order of the list content is irrelevant, for example something like a shopping list or the ingredients of a recipe. It does not matter what order you attain the items, so long as they are all there in the end.

2. **How do you change the bullet style of unordered list items?** By adding the `list-style-type` property to the `ul` selector in the stylesheet and giving it a value of either `circle`, `square`, or `disc`.

3. **When should you use an `ordered list` vs. an `unordered list` in your HTML document?** An `ordered` list should be used when the order of execution of the list items matter, for example if you need to follow step-by-step instructions to complete something like baking a cake or following directions to a location.

4. **Describe two ways you can change the numbers on `list items` provided by an `ordered list`?** We can add either the `type` attribute and giving it a value of `i` to make the numbers be roman numerals or we can add the `start` attribute and give it a number value which changes the starting number of the list. 


## CSS - The Box Model

1. **Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: "The Box Model"?** Content is King, and as the King he sits in the middle of his box castle. His guard, the Royal Padding, maintains a certain amount of space between the Content King and the inside of the box castle border walls. However, the Marginal Guard also protects the box castle border walls - but on the outside! They protect the outside of the walls by maintaining a certain amount of distance between them and the outer elements.

2. **List and describe the four parts of an HTML elements box as referred to by the `box model`** 
	- Content Box: where your content is displayed.
	- Padding Box: the space between your content and the border
	- Border Box: the border immediately surrounding the padding
	- Margin Box: the space outside of the border, which maintains space between other elements and their boxes.


## JavaScript - Arrays, Conditionals, Loops, Operators & Expressions

1. **What `data types` can you store inside of an `Array`?** We can store strings, numbers, booleans, null, undefined, objects, other arrays and even functions inside of an array.

2. **Is the `people` array below a valid JavaScript array? If so, how can I access the values stored? If not, why?**

```
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

It *is not* a valid array because of the entry `fishing:hiking:rock_climbing` which is an invalid entry. It looks like its trying to be an object but if that is the case it needs to be wrapped in curly braces.

3. **List 5 shorthand operators for assignment in JavaScript and describe what they do**
	- Addition Assignment: `+=` adds two variables together and sets the sum as the new value of whatever variable is on the left hand side.
	- Subtraction Assignment: `-=` subtracts the variable on the right from the variable on the left and sets the value of the left variable as whatever the difference is.
	- Multiplication Assignment: `*=` multiplies both variables together and sets the value of the variable on the left to whatever the new product is.
	- Division Assignment:  `/=` divides the variable on the left by whatever is on the right and sets the new value of the left variable to be whatever the quotient is.
	- Remainder Assignment: `%=` divides the variable on the left by whatever is on the right and sets the new value of the left variable to be whatever the remainder of the division is.

4. **Read the code below and evaluate the last expression and explain what the result would be and why**

```
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```
This will evaluate to "10dog". `a + c` or `10 + false` will just evaluate to 10 because false is another way of saying `0`, so therefore we're not adding anything to `a`. Then we add `b`, or `dog` to it which results in `10dog`.


5. **Describe a real world example of when a conditional statement should be used in a JavaScript program** We could use a conditional statement to determine whether or not we should turn the headlights of a car on or off. *If* it's dark outside we need to turn the headlights on, otherwise we don't need to turn them on.

6. **Give an example of when a loop is useful in JavaScript** A loop is useful if we need to execute a code block until a certain condition is met. For example, if we have an array of random numbers and we want to keep adding the numbers together until we reach a sum of 100, we can loop through the array and add the numbers together until we meet that threshold or until we reach the end of the array.

## Things I Want to Know More About
- What is bitwise assignment
- What is shift assignment
- Why does JS sometimes create shallow copies of an array vs. making an array a direct copy. In other words, if I have one array, `arrayA` and I write the line `let arrayB = arrayA`, why does making changes to `arrayB` also affect `arrayA`? I understand that it *does* affect both, but *why* does JavaScript handle it this way.
