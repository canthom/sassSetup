# sassSetup
A ReadME file about the best ways to structure Sass Files

## Types of Sass Structures

### Simple Structure
You should use this one for your small projects. This structure is very minimal : 

* main.sass : this file contains only the imports from the other files.
  * _base.sass : contains all the resets, variables, mixins and utility classes.
  * _layout.sass : all the Sass code handling the layout.
  * _components.sass : everything that is reusable - buttons, navbars, cards...
  
  
