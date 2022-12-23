# Day 3 Notes

## Classes, Objects, Recursion and Fixtures

### Classes and Objects

• What are they?
  > Objects: Everything in Python is an object! They are an encapsuation of variables and function in a single entity.
  > Classes: A template to create your object

• Init
  > A function thats called when initiating a class. It assigns values in a class.

### Recursion

• It's essentially chipping away at a problem, breaking them down into smaller chunks trivial enough to solve. A function will continue to call itself and repeat its behavior until a condition is met to return a result.

• All recursive funtions share a common structure made up of two parts: Base cand and Recursive case.

• Recursive calls have their own execution context, to maintain state during recursion you have to either keep the state in global scope or thread the state through each recursive call so that the current state is part of the current call’s execution context

### Fixtures

• Fixtures are functions that can be used instead of running the same code for every test. We can attach a fixture function to the tests and it will run and return the data to the test before executing each test.

### Things I want to know more about

I would like to learn more about how recursion works and how to write python better

#### Sources

https://www.learnpython.org/en/Classes_and_Objects

https://realpython.com/python-thinking-recursively/

https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage

Click to return [Home!](../README.md)
