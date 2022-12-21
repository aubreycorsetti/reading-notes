# Day 1 Notes

## Testing and Modules

### In Tests We Trust

• TDD stands for Test Driven Development

• Unit tests- what are they?
  > Unit tests are pieces of code to exercise the input, output and behavior of your cide. These can be written anytime.

• Structure your testing!
  > The most widely used method is the AAA also known as, Arrange, Act and Assert.
    • Arrange: organize the data needed to execut that piece of code (input)
    • Act: execute the code being tested/exercise the behavior
    • Assert: check to if the result (output) is the same as you were expecting.

• The Cycle (3 steps):

  1. 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)

  2. ✅ Write the feature and make the test pass! (you can dance after that)

  3. 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)

### If Equals Main

• Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.

• If you import this script as a module in another script, the __name__ is set to the name of the script/module.
Python files can act as either reusable modules, or as standalone programs.

• if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

### Recursion

• What is Recursion?
  > The process in which a function calls itself directly or indirectly, the corresponding funtion is called a recursive function.

• Why do we need it?
  > It can make our code shorter and easier to read/write.

*Recursion uses more memory becayse the rec. func. adds to the stack with each rec. call and keeps the values there until the call is finished.*

• Summary of Recursion:

  > There are two types of cases in recursion i.e. recursive case and a base case.
  > The base case is used to terminate the recursive function when the case turns out to be true.
  > Each recursive call makes a new copy of that method in the stack memory.
  > Infinite recursion may lead to running out of stack memory.
  > Examples of Recursive algorithms: Merge Sort, Quick Sort, Tower of Hanoi, Fibonacci Series, Factorial Problem, etc.

#### Sources

https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/

https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932

https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/

Click to return [Home!](../README.md)
