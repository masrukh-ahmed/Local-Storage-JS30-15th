Ok so in the first try i focussed on understanding the concepts used in the tutorial, most of them are known to me since i learnt them from the previous tutorials.
The new things i learned are :

1. the method to reset a form element using .reset();
2. Next learnt about what Local Storage actually is, through some external resources and in the process also learnt a few things about cookies and sessions storage.

First of all Local Storage is a web storage object which are not sent to the server with each request. The data stored in a local storage can survive a full page refresh/reload and even a full browser restart.
The most used methods/properties of local storage have been noted down in the note:
![Local Storage note on it's methods](local_storage_methods_notes.jpg)

Some of the most important things to remember while using local storage are:
![Key points to remember while using local storage](local_storage_notes1.jpg)

In this process learnt a bit more about how we can use the JSON methods mentioned above in these types of scenarios.

3. Next learnt about the concept of event delegation which we used in adding click event listeners to each checkboxes without adding event listener to each checkbox but rather to it's parent element.

In short, Event Delegation is basically a pattern to handle events efficiently. Instead of adding an event listener to each and every similar element, we can add an event listener to a parent element and call an event on a particular target using the .target property of the event object. That's all there is to it.
