# BEM_CSS
The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project.

Here’s an example of what a CSS developer writing in the BEM style might write:


.btn {}          /* Block component */


.btn__price {}  /* Element that depends upon the block */ 

.btn--orange {}   /* Modifier that changes the style of the block */

.btn--big {}      /* Modifier that changes the style of the block */



In this CSS methodology a block is a top-level abstraction of a new component, for example a button: .btn { }. This block should be thought of as a parent. Child items, or elements, can be placed inside and these are denoted by two underscores following the name of the block like .btn__price { }. Finally, modifiers can manipulate the block so that we can theme or style that particular component without inflicting changes on a completely unrelated module. This is done by appending two hyphens to the name of the block just like btn--orange.
