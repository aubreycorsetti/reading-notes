# Day 9

## Forms and JS Events

### HTML Forms

1. Why are forms so important in web development?

  > Because they are used for collecting user data.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

  > You can't have a form element inside another form element.
  > Every time you hae a set of radio buttons you should nest them inside your < fieldset > element.
  > Clearly title your form

3. List 5 form elements and explain their importance.

  > < label >: this is how we define a label for an HTML widget form.
  > < fieldset >: sections your form
  > < input >: sets the type of input we want to receive whether it be a button, check box etc.
  > < select >: a control that provides a menu of options
  > < button >: interactive element activated by the user then once activated performs a programmable action

### Learn JS

1. How would you describe events to a non-technical friend?

  > When you go on a website and click a button, a reaction happens within the computer code that has something like an information box come up. Thats whats called an event, when an action happens in the system

2. When using the addEventListener() method, what 2 arguments will you need to provide?

  > the name of the event we want to register and the code that we want to run in response.

3. Describe the event object. Why is the target within the event object useful?

  > The event object is a parameter with names such as event, evt or e. The target within the event object is useful because its the button itself.

4. What is the difference between event bubbling and event capturing?

  > Event Bubbling
    * "bubbles up" (starts running through code) from the innermost element that was clicked. It checks to see if the direct parent of the element clicked has a click event and runs it if so, if it does not then it moves on to the next immediate ancestor that does the same thing and so on.
  
  > Event Capturing
    * Opposite of bubbling and starts from the outer-most element. So it will start with checking to see if the outer-most ancestor html has a click event and continues to the next element after that and so on.

Click to return [Home!](../README.md)
