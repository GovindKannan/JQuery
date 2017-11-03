JQuery


Description:
This is just a refreshing course for JQuery. Just touching on the basics for reference purpose.

Pre-requisites:
* Basic understanding on JS
* Basic understanding on CSS


Lesson 3: Traversing through DOM Tree

In this lesson we will understand how to traverse through DOM tree to access different elements.

* $("#element-id").next() will fetch the next element in the tree.
* $("#element-id").prev() will fetch the previous element.
* $("#element-id").parent() will fetch the parent of the current element.
* $("#element-id").parents() will fetch all the parents of the element in the dom tree.
* $("#element-id").children() will fetch all the childrens of the current element.
* $("#element-id").find(".class-name") finds all elements with the class name attribute provided.
* $("#element-id").closest(".class-name") find the closest dom element having the class name provided.


Chaining in JQuery:

We can use the above methods to create a chain where one statement updates multiple elements
* eg: $("#current-element-id").css(border:"2px solid red")

          .next().css(color: "red")

          .closest("H1").css(color:"blue");
