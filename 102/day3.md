# Day 3

## Learning JavaScript

### What is JavaScript?

> JavaScript is an object oriented programming language which makes your website interactive!

### JavaScript Identifiers

>All JavaScript variables must be identified with unique names. These unique names are called identifiers.
Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).
The general rules for constructing names for variables (unique identifiers) are:

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter.
* Names can also begin with $ and _
* Names are case sensitive (y and Y are different variables).
* Reserved words (like JavaScript keywords) cannot be used as names.

### Embed or include

>You can either embed the JavaScript code directly inside the HTML file, or you can put a line in the HTML file that will include the external JavaScript file.

### Console.log

>Most of the web browsers provide what is called a "JavaScript console". Which is an additional window that normally is not visible, where the browser can print out warnings and errors generated by the execution of the JavaScript code. The developer can also print information to this console using the console.log() call.

### The two ways to receive input

Prompt
>The fist one is called prompt. It will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. When the user presses OK, the value in the text box will be returned by the prompt() function.

* For example:

< script >

var name = prompt ( "your name " , "  " ) ;
document.write ( "Hello", name );
< / script >

Confirm
>The other pop-up is not really an input method. It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.

### Declaring Variables

There are 4 different variables.

* Var (not used)
* (none)
* Let -- can be changed
* Const -- constant, cannot be changed

LET:

*EX:
Input: Let x = 10;

    x is the variable
    = gives value
    10 is the value
Output from the console would be 10.
If you were to enter x+x the console would show 20.

CONST:

*EX:
The best way to explain this is by a users name. When prompted to enter a name the console will remember that name and it will not change.
    console.log (insertnamehere)

### Data Types

* Boolean -- True/False
* Strings -- "Words wrapped in quotes"
* Numbers/Integers -- 10, 50, no quotes

### JavaScript is very interactive and so much goes into it

Click to return [Home!](../README.md)