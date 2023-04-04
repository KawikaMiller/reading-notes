# Reading - Class 02

This information covers more in-depth information about HTML elements, how to apply CSS styles, and some basic information about JavaScript conditional statements and operators.

## Introduction to HTML - cont.

1. **Why is it important to use semantic elements in our HTML?** Semantic elements in our HTML help to give us context about what the element represents and the content within it. It also helps with Search Engine Optimization as well as accessibility with screen readers.

2. **How many levels of headings are there in HTML?** There are 6 levels of headings in HTML, `<h1>` through `<h6>`

3. **What are some uses for the `<sup>` and `<sub>` elements?** Superscript, or `<sup>` elements can be used when we need to designate dates, Jan 1<sup>st</sup>, or exponents, x<sup>10</sup>, while subscript, or `<sub>` can be used for things atom designation in chemical formulas, like H<sub>2</sub>0.

4. **When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?** We must include the `title` attribute. When we do so, we can see the full term for what the abbreviation means when we hover over the abbreviated element.

## Learn CSS

1. **What are ways we can apply CSS to our HTML?** 
	- Internal Stylesheets: placed inside the `<head>` element of our HTML document. 
	- Inline Styles: placed as a `style` attribute within an HTML tag
	- External Stylesheets: a separate `.css` file that is linked to the HTML document within the `<head>` element.

2. **Why should we avoid using inline styles?** Because it makes the HTML document harder to read and harder to edit if we ever need to make changes in the future.

3. **Review the block of code below and answer the following questions:**

```
h2 {
     color: black;
     padding: 5px;
   }
```

- **What is representing the selector?** h2
- **Which components are the CSS declarations?** Everything within the curly braces
- **Which components are considered properties?** Each individual line within the curly braces. The keywords `color` and `padding` are the property *names* while `black` and `5px` are the property *values*



## Learn JS

1. **What data type is a sequence of text enclosed in single quote marks?** The `string` data type is a sequence of text encloses in either single or double quote marks.

2. **List 4 types of JavaScript operators** 
	- The assignment operator `=` 
	- The not operator `!` 
	- The strict equality operator `===`
	- The modulo uperator `%`

3. **Describe a real world Problem you could solve with a Function** A real world problem, such as determining if we need to go buy more beer, could be solved by creating a function that checks if a variable, `beers`, is at or below a certain threshold. 

```
function needMoreBeers (beersInFridge) {
   if (beersInFridge <= 1) {
      return 'need more beer';
   } else return 'you have enough beer';
}
```

### Conditionals - Making Decisions In Your Code

1. An if statement checks a **condition** and if it evaluates to **true**, then the code block will execute.

2. **What is the use of an `else if`?** We use an `else if` to provide an additional conditional check to evaluate which has its own code block that will execute if the condition evalutes to `true`.

3. **List 3 different types of comparison operators**
	- Greater / Less Than, `>` or `<`
	- Identical / Not Identical, `===` or `!==`
	- Greater / Less Than or Equal To, `<=` or `>=`

4. **What is the difference between the logical operators `&&` and `||`?** The logical operator `&&` means that all conditions chained together with the `&&` operator(s) must evaluate to true in order for the following code block to be executed, whereas `||` means that at least one of the conditions must evaluate to true in order for the following code block to be executed. For example

```
if (x && y && z) {
// do stuff
} else if (a || b) {
do other stuff
};
```

## Things I Want to Know More About
- n/a
