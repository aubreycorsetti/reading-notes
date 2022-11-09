# Day 2 Reading Notes

## Passing Functions as Props

### React Docs- lists and keys

• What does .map() return?

  > .map() returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.)

• If I want to loop through an array and display each value in JSX, how do I do that in React?

  > By using the .map() method.

• Each list item needs a unique ____.

  > Key (a special string attribute).

• What is the purpose of a key?

  > Key helps React identifu the items that have changed/added and or removed.

### The Spread Operator

• What is the spread operator?

  > A useful and quick syntac for adds/combines arrays or objects and spreading an array out into a functions arguments.

• List 4 things that the spread operator can do.

  > It can copy an array, combine objects, add an item to a list and use an array as arguments.

• Give an example of using the spread operator to combine two arrays.

> const hello = { hello: "😋😛😜🤪😝"}
> const cameron = { cameron: "🙂🙃😉😊😇🤩!"}
> const helloCameron = {...hello,...cameron}

• Give an example of using the spread operator to add a new item to an array.

> const fruit = ['🍏','🍊','🍌']
> const moreFruit = ['🍉', '🍍', ...fruit]

• Give an example of using the spread operator to combine two objects into one.

  > const objectOne = {hello: "🤪"}
  > const objectTwo = {world: "🐻"}
  > const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

### How to Pass Functions Between Components

• In the video, what is the first step that the developer does to pass functions between components?

  > Create a function wherever the state is that we are going to change.

• In your own words, what does the increment function do?

  > adds one "count".

• How can you pass a method from a parent component into a child component?

  > by using "props"

• How does the child component invoke a method that was passed to it from a parent component?

  > by using "this.props.functionname()"

### Things I want to know more about

> I would like to know more about combining arrays!

### Sources

https://www.geeksforgeeks.org

Click to return [Home!](../README.md)
