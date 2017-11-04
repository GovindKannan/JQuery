JQuery


Description:
This is just a refreshing course for JQuery. Just touching on the basics for reference purpose.

Pre-requisites:
* Basic understanding on JS
* Basic understanding on CSS


Lesson 5: Event Handling


All action performed in the web page corresponds to an event. In this lesson we will learn how to handle events using jQuery.

Binding and Unbinding Events.
* on(): Binds an event to elements.
  * -----$("#id").on("event-name", function(){  ---  });
* off(): Unbinds event from matched elements.
  * -----$("#id").off("event-name");


Event Helpers
instead of $("#id").on("click", fucntion(){});, we can choose to use event helpers.
  * $("#id").click(function(){}); -- Can be used for all the events for jQuery!

event object can be propagated into these methods and can be accessed inside the function.
  * $("#id").click(function(e){console.log("event triggered from : " + e.target});

Window load events:

* $(document).ready(function(){..}) is same as $(function(){..}) and $(document).on("ready", function(){ .. });

* $(window).load() == $(window).on("load", function(){ .. })
  Difference between document.ready and window.load is that window.load is performed only after all the elements are loaded including the image. document.ready is fired as soon as the page is ready to load.


  Important links:
  * Event types: https://www.w3schools.com/jquery/jquery_ref_events.asp
