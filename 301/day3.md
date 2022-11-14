# Day 3 Notes

## React and Forms

### React Docs - Forms

• What is a ‘Controlled Component’?

  > A controlled component is an input form element whose value is controlled by React.

• Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

  > Update as the user types. With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

• How do we target what the user is entering if we have an event handler on an input field?

  > by using "this.state.value"

### The Conditional (Ternary) Operator Explained

• Why would we use a ternary operator?

  > Because it is DRY and good for decision making in place of long if/else statements

• Rewrite the following statement using a ternary statement:

  if(x===y){
  console.log(true);
} else {
  console.log(false);
}

  > x===y ? console.log(true) : console.log(false)

### Sources

https://reactjs.org/docs/forms.html

### Things I want to know more about

> I would like more knowledge in writing ternary operators! They're so DRY!

Click to return [Home!](../README.md)
