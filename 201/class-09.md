# Reading - Class 09

These notes will cover HTML Forms and how to create them in order to get user input as well as JS events, event listeners, and callback functions (event handlers) and how we can use them to manipulate the DOM.

## HTML - Forms

1. **Why are forms so important in web development?** They allow us to get user input for various reasons and send that information somewhere else, one of the more familiar implementations of this is to do things like logging in to a website using your username and password.

2. **When designing a form, what are some key things to keep in mind when it comes to user experience?** We should keep in mind things like how easy it is to interpret what kind of information the form is asking for. We should keep forms as simple as possible as to not overwhelm the user.

3. **List 5 form elements and explain their importance:**
	1. `<input>` Where the user enters some kind of information to the form
	2. `<label>` How the developer can describe to the user what kind of information is being asked for.
	3. `<button>` typically used to submit the form when all input elements have been filled but can also be used to do things like reset the form.
	4. `<form>` the form element itself which would contain all input elements, labels, buttons, etc. If there are multiple forms this is how we distinguish between forms and how we keep all relevant information grouped together.
	5. `<textarea>` Similar to an `<input>` element with the `type="text"` attribute however it offers a larger area to type into. Typically used when we want more than just a few words or one line to be entered.


## JS - Events

1. **How would you describe events to a non-technical friend?** Events are essentially things that happen, like an action, which can potentially trigger some kind of effect. For example, sending a text could be an event and when that action happens an effect is triggered - that effect would be the person you send a text to gets a notification on their phone. Another example could be flipping a light switch as an event. If the light is off and you flip the switch, the effect would be that the light gets turned on; If the light is on then flipping the switch would result in the light being turned off.

2. **When using the `addEventListener()` method, what 2 arguments will you need to provide?** The first argument is the type of event that is being listened for while the second argument is the callback function to be triggered when the event occurs.

3. **Describe an event object. Why is the target within the event object useful?** An event object is just a regular JavaScript object that holds a bunch of properties which describe the event. The `target` property is particularly useful because it gives us the specified HTML element / DOM Node that the event was triggered from.

4. **What is the difference between event bubbling and event capturing?** Event bubbling describes how the browser handles events targeted at nested elements. Events will fire on the innermost element and work outward, whereas event capturing is the same as event bubbling but in reverse. It triggers on the most outward element and then keeps moving inward until the target is reached.

## Things I Want To Learn More About
- I think I need a visual example for event bubbling and event capturing. I understand it in essence but seeing it in action would help.
- Are all event handlers callback functions? But not all callback functions are event handlers?