JQuery


Description:
This is just a refreshing course for JQuery. Just touching on the basics for reference purpose.

Pre-requisites:
* Basic understanding on JS
* Basic understanding on CSS


Lesson 5: Animation


animate method:
* $("#id").animate({"css property": "values"}, transition time, transition type(linear/swing), call back function):// swing is default
  * ----- $("#id").animate({"width":"50px","height":"20px" }, 2000, "linear", function(){callback});


Fade methods:
* Instead of putting code like $("#id").animate({"opacity":"0.5"}), we can put our code like
  * ---$("#id").fadeOut(tranistion time in ms); -- puts opacity to 0 (transparent)
  * ---$("#id").fadeTo(transition-time, opacity-value);


Show, Hide and Toggle:
  * $("#id").hide(transition time) - hides the element with a zoom out and slide out effect.
  * $("#id").show(transition time) - displays back the object with a zoom in effect.
  * $("#id").toggle(transition time) - hides or shows based on the current state of the element.


Slide:
  * $("#id").slideUp(transition-time, callback-function);
  * $("#id").slideDown(transition-time, callback-function);
  * $("#id").slideToggle(transition-time, callback-function); -- slides up or down depending on current status of the element.

  Important links:
  * Event types: https://www.w3schools.com/jquery/jquery_ref_events.asp
