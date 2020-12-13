# sassSetup
A ReadME file about the best ways to structure Sass Files. 
By default, CSS doesn't have a rigid structure, which can make it hard to keep a clean and maintaainable codebase. It's important to think of how you will structure your code before you even write a line. You need to make a plan and stick with it. Don't put too many rules into your selectors, you can separates this rules in order to keep your code readable.


## Types of Sass Structures

### Simple Structure
You should use this one for your small projects. This structure is very minimal : 

* main.sass : this file contains only the imports from the other files or comments.
  * _base.sass : contains all the resets, variables, mixins and utility classes.
  * _layout.sass : all the Sass code handling the layout.
  * _components.sass : everything that is reusable - buttons, navbars, cards...
  
  
