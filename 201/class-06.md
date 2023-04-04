# Reading - Class 06

These notes will cover basic information about JavaScript objects as well as introductory information about the DOM, or Document Object Model.

## JavaScript - Object Basics

1. **How would you describe an object to a non-technical friend you grew up with?** An object is like a template for something. Think of a "car" as the template; All cars typically have similar properties like doors, windows, tires, paint color, an engine, etc. However, the amount of doors, the color of the car, the engine type, etc. can all vary from car to car. Even though the *values* of each *property* can vary from car to car, they are still all considered a "car" object.

2. **What are some advantages to creating object literals?** Creating an object literal, or object initializer, allows us to create a template for instantiating many different "copies" or "versions" of our object.

3. **How do objects differ from arrays?** An object is a singular "thing" with multiple different key:value pairs that are attached to it whereas an array are multiple "things" within a container. Additionally, related objects all share a similar "template" whereas every array is unique to itself.

4. **Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.** Dot notation is used when we know the name of the property of an object we want to access whereas bracket notation is used whenever we are using a variable to access a property of an object. 

5. **Evaluate the code below. What does the term this refer to and what is the advantage to using this?** 

```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

"this" refers to the currently instantiated object that is accessing the property. So for example, say we had two different `Dog` objects, the one in the code snippet above and another one with the name 'Fido' and an age of '4'. When we access the property `humanAge` on `Spot`, the function will console log 'Spot is 14 in human years' and if we do the same thing with 'Fido' the function will console log 'Fido is 28 in human years'.

The advantage of using `this` is that we are able to ensure properties and methods that utilize `this` are making sure that the information they are referencing is specific to the object that is using the `this` keyword.

## Introduction to the DOM

1. **What is the DOM** The DOM, or Document Object Model, is a representation of a webpage and it's content hierarchy. Each piece of the DOM are represented as nodes and objects which make it easier for us to understand and represent how content is being displayed &/o manipulated.

2. **Briefly explain the relationship between JavaScript and the DOM.** Since JavaScript is an object oriented programming language and the DOM is a series of nodes and objects, this helps JavaScript to understand what is going on in the DOM and how to use it to interact &/o manipulate a webpage. Essentially, the DOM is the hierarchy and structure of a webpage represented as an object and JavaScript is the language through which that object is being interpreted and altered.

## Things I Wish To Know
-Is there any way to visually see a representation of the DOM while still developing in VSCode or anywhere else?
