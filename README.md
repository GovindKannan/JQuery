JQuery


Description:
This is just a refreshing course for JQuery. Just touching on the basics for reference purpose.

Pre-requisites:
* Basic understanding on JS
* Basic understanding on CSS


Lesson 5: Update Elements using Jquery


Add/Remove Attributes
* removeAttr(): removes and attribute from the element.
  * -----$("#id").removeAttr("att-name");
* attr(): Read / Set an Attributes
  * -----$("#id").attr("attr-name"); -- Reads attr value
  * -----$("#id").attr("attr-name", "attr-value"); -- sets attribute value


CSS update with JQuery
* $("#id").css("top", "200px"); -- Single CSS property update
* $("#id").css("top", "200px").css("left", "100px") -- chaining update
* $("#id").css({ -- instead of chaining we can pass as object
      "top" : "40px",
      "left" : "20px",
      "opacity" : "0.5"
    });


Add / Remove classes
* addClass(): Add class to the element.
  * -----$("#id").addClass("class-name")
* removeClass(): Remove class to the element.
  * -----$("#id").removeClass("class-name")
* toggleClass(): Adds / remove class based on current state.
  * -----$("#id").toggleClass("class-name")
