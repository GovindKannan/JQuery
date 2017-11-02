JQuery


Description:
This is just a refreshing course for JQuery. Just touching on the basics for reference purpose.

Pre-requisites:
* Basic understanding on JS
* Basic understanding on CSS

Lesson 2: JQuery Selectors

Selectors enable us to grab contents from web page. The following are the ways we can use selectors

  * By ID: $("#element-id")
  * By element type: $("h3 <or any element type like input etc.>")
  * By classes: $(".className")


JQuery Filters:

JQuery filters enables us to refine our selector search of elements. eg, we can use filters to refine our jquery selector to fetch only first p tags inside a div. Filters always start with a :.
eg:
  * $("div p:first") will fetch the first p inside all the div tags in the dom.
  * first
  * first-child
  * last
  * even - grabs all the even elements
  * odd - grabs all the odd elements
  * not - $("div:not('<#element-id in single quotes>')") - Excludes the id included in single quotes
  * lt - $("div li:lt(3)") - Fetches all the list elements having index less than 3
  * gt - $("div li:gt(3)") - Fetches all the list elements having index greater than 3
  * $("div[class]") - Fetches all divs having a class attribute. This is an attribute search
  * $("div[name=some name]") - Same as attribute search but added parameter of the attribute value (in this case elements with name attribute with 'some name' will be returned)


Note:
* document.getElementByID("element-id")==> $("#element-id"), the jquery select will always return a jQuery object as opposed to the getElementByID which returns the html element.

Usefull links:
* Filters: https://api.jquery.com/category/selectors/
  Changes Made: None
