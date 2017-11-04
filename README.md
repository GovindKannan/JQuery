JQuery


Description:
This is just a refreshing course for JQuery. Just touching on the basics for reference purpose.

Pre-requisites:
* Basic understanding on JS
* Basic understanding on CSS


Lesson 4: Add / Remove elements using JQuery

We will learn about the different JQuery methods that can be used to add contents dynamically in our application view.
* append(): adds content to the bottom of the element.
  * -----$("#id").append("<h1>some text</h1>")
* prepend(): adds content to top of the element.
  * -----$("#id").prepend("<h1>some text</h1>")
* before(): adds content before element as a new node.
  * -----$("#id").append("<h1>some text</h1>")
* after(): adds content after the element as a new node.
  * -----$("#id").after("<h1>some text</h1>")
* html(): Changes teh whole html of the element.
  * -----$("#id").html("<h1>some text</h1>")
* text(): Changes the text of an element.
  * -----$("#id").text("some text")

Now we will focus on how to remove elements from dom using JQuery.
* empty(): This will remove all the contents inside the tag
  * -----$("#id").empty();

* remove(): This will delete the element itself instead of clearing the contents inside.
  * -----$("#id").remove();


Wrapping and Unwrapping of elements

* wrap(): Box an element with in another Tag.
  * ----$("#id").wrap("<just opening Tag>");
* unwrap(): Unbox an element from its immediate parent.
  * ----$("#id").unwrap();
* wrapAll(): wraps all of the elements in a single tag.
  * ----$("section").wrapAll("<opening tag>");
