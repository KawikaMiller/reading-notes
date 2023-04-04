# Reading - Class 07

These notes will cover Domain Modeling, the basics of HTML tables, and JavaScript constructors.

## Domain Modeling

1. **Explain why we need domain modeling:** Domain Modeling is a way of establishing the problem domain of a given situation and trying to produce a solution to that problem. In other words, identifying what the problem is, how we might solve it within a set of given parameters, and what those methods would look like. 

## HTML Table Basics

1. **Why should tables not be used for page layouts?** Tables should not be used for page layouts because it's not semantically appropriate and it interferes with how screen readers interpret information. Additionally, table elements are sized according to their content so we need to go through extra steps to get the sizing of each cell of content to appear correctly.

2. **List and describe three semantic HTML elements used in a `table`.** `<td>`, `<tr>`, and `<th>`, which stand for Table Data, Table Row, and Table Header, respectively. Table Data are the individual cells of information while Table Rows are how we encapsulate that information - much like how List Items, `<li>`, work with Ordered `<ol>` & Unordered `<ul>` Lists. Table headers can span multiple rows or columns and are used to help give a table context as to what information is beind displayed.

## Constructors

1. **What is a constructor and what are some advantages to using it?** Constructors are functions that create a new object, this offers a way to quickly create multiple instances of any given object.

2. **How does the term `this` differ when used in an object literal vs. when used in a constructor?** When we use `this` in an object literal its often used as a way to access that specific object's property values within something like that object's methods `propertyB: function () {this.propertyA += something}` vs. when we use the keyword `this` in a constructor its used to define a property value in the constructed object by using the arguments passed into the constructor function `this.propertyC = argument;`.

## Object Prototypes Using a Constructor

1. **Explain prototypes and inheritance via an analogy from your previous work experience.** The longest job I ever held was at a small pizzeria so let's consider each pizza as an object. Whenever someone orders a pizza they ask for their preferred toppings and the size of the pizza, in terms of key-value pairs we could think of something like `pepperoni: double` or `size: large`. However, typically its implied that every pizza gets cheese and sauce as well. Instead of having to declare that every pizza object gets cheese and sauce, we can store that information in the `Pizza.prototype` property so that every pizza object that we instantiate inherits that information, saving us time (in regards to the order taking process) or memory (in regards to programming).

## Things I Want To Know More About
- What is the fundamental differences between instantiated and initialized?
- Not really a question or anything I just feel like i need more experience / practice with `prototype` to better understand and cement that knowledge in my head.
