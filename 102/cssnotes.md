# Day 3

## Learning CSS

### What is CSS?

**CSS stands for Cascading Style Sheets.**
> It is a language for specifying how documents are presented to users- how they are styled, laid out etc. Css is a rule based language you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your page.

1. CSS rule opens with with a *selector* (the HTML element we are going to style)
    * EX: (< h1 >)
2. Next use curly brackets {}
3. Inside the braces will be one or more declarations, which take the form of property and value pairs. We specify the property before the colon, and we specify the value of the property after the colon.
    * EX:
  h1 {
  color: red;
  font-size: 5em;
}
4. This example contains two declarations, one for color and the other for font-size. Each pair specifies a property of the element(s) we are selecting (< h1 > in this case), then a value that we'd like to give the property.

### *CSS properties have different allowable values, depending on which property is being specified*

* **Property:** the thing about HTML you want to change.

* **Style:** The value you want to change to/ the actual style you want to give the element.

> **A CSS stylesheet will contain many such rules, written one after the other.**

There are 3 ways to insert CSS:

1. **External:** *defined with a link to an external file*
2. **Internal:** *defined with a style tag in HTML*
3. **Inline:** *defined with the style attribute in the HTML element itself*

Time to get STYLIN'!

Click to return [Home](README.md)