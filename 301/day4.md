# Day 4 Notes

## Putting it all Together

### Thinking in React

• What is the single responsibility principle and how does it apply to components?

  > Single responsibility principle is a component should do only one thing. If it ends up getting bigger it should be made into smaller subcomponents.

• What does it mean to build a ‘static’ version of your application?

  > Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.

• Once you have a static application, what do you need to add?

  > You'll need to build components that reuse other components and pass data using props.

• What are the three questions you can ask to determine if something is state?

  > *Is it passed in from a parent via props? If so, it probably isn’t state.*
  > *Does it remain unchanged over time? If so, it probably isn’t state.*
  > *Can you compute it based on any other state or props in your component? If so, it isn’t state.*

• How can you identify where state needs to live?

  > • Identify every component that renders something based on that state.
  > • Find a common owner component (a single component above all the components that need the state in the hierarchy).
  > • Either the common owner or another component higher up in the hierarchy should own the state.
  > • If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

### High Order Functions

• What is a “higher-order function”?

  > Functions that operate on other functions by taking them as arguments or returning them.

• Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

  > It is returning what is greater than n

• Explain how either map or reduce operates, with regards to higher-order functions.

  > With reduce, it builds value by repeatedly taking a single element from the arary and combining it with the current value. So its using a function that operates on another function.

### Things I want to know more about

> I would like to know more about how to write this.

### Sources

https://cdnify.com

https://reactjs.org/docs/thinking-in-react.html

Click to return [Home!](../README.md)
