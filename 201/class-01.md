# Class 01

## Prepwork

### *Getting Started*

 1. Compose a short poem describing how HTTP sends data between computers.
    > POEM TITLE: I want a burger... I call over the server to order my burger. The server sees I'm hungry and reports my order to the chef who makes my burger. The server sees I'm hungry and brings me back what the chef created for me. I've received my burger. A wonderful masterpiece indeed.
 2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

    > * The browser parses the HTML file first, and that leads to the browser recognizing any < link >-element references to external CSS stylesheets and any < script >-element references to scripts.
     > * As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from < link > elements, and any JavaScript files it has found from < script > elements, and from those, then parses the CSS and JavaScript.
    > * The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
    > * As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

    Source [Here!](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

 3. How can you find images to add to a Website?
    > Go to Google, click on tools, click usage rights then click creative common licenses, find yout image then right click. Open your image in a new tab, and you are able to copy the image link from there.
 4. How do you create a String vs a Number in JavaScript?
    > You create a string by enclosing the value with single quotation marks. You create a number without quotes.
    * String EX: let myVariable = ' value ' ;
    * Number EX: let myVariable = 8 ;
 5. What is a Variable and why are they important in JavaScript?
    > A variable is something that holds value. It allows you to write code with meaning.

### *Introduction to HTML*

 1. What is an HTML attribute?
    > An attribute is something that contains extra information about the element that won't show up in the contents.
 2. Describe the Anatomy of an HTMl element.
    * **the opening tag**
        > This contains the name of the element wrapped in open and closing angle brackets.
    * **the content**
        > the content of the element
    * **the closing tag**
        > this is the same as the opening tag but contains a forward slash before the element name. 
 3. What is the Difference between < article > and < section > element tags?
    * **article tag**
        > contains a block of content that makes sense on its own without the rest of the page.
    * **section tag**
        > groups together a single part of the page that constitutes as a single functionality
 4. What Elements does a “typical” website include?
    > They will have a header, nav, body, main and a footer
 5. How does metadata influence Search Engine Optimization?
    > with metadata you are able to have all the content of your page re-written in any human language!
 6. How is the < meta > HTML tag used when specifying metadata?
    > meta tags always go inside the head element. They are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

### *How to start to design a website*

 1. What is the first step to designing a Website?
    > Ask yourself "What do I want to accomplish", "How will a website help me reach my goals" and "What needs to be done, and in what order, to reach my goals"
 2. What is the most important question to answer when designing a Website?
    > What do I want to accomplish?

### *Semantics*

 1. Why should you use an < h1 > element over a < span > element to display a top level heading?
    > H1 element is a semantic element which gives the text it wraps around the role/meaning of "a top level heading on your page while a span element will only look like a header but have no semantic value.
 2. What are the benefits of using semantic tags in our HTML?

    > * Search engines will consider its contents as important keywords to influence the page's search rankings.

    > * Screen readers can use it as a signpost to help visually impaired users navigate a page

    > * Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes

    > * Suggests to the developer the type of data that will be populated

    > * Semantic naming mirrors proper custom element/component naming

### *What is JavaScipt*

 1. Describe 2 things that require JavaScript in the Browser?
    > Interpreted versus compiled code:
    > Server-side versus client-side code:
 2. How can you add JavaScript to an HTML document?
    > by using script element in closing brackets.

Click to return [Home!](../README.md)
