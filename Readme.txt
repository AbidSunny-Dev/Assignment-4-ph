ques -1 : getElementById: Finds one specific element by its unique ID.
          getElementsByClassName: Finds all elements with a certain class and puts them in a list
          querySelector: Uses CSS selectors (like - class or #id ) to find only the first match.
          querySelectorAll: Uses CSS selectors to find all matches and puts them in a list. Perfect  to change a whole group of items at once.





ques - 2 : Step 1:  we need to create document.createElement to build the tag in the computer's memory.
	   Step 2: we need to fill the text content.
           Step 3:we need to  find an existing element on the page where we want the new item to live using querySelector.
           Step 4: we need to  Use parent.appendChild(newElement) to stick it at the end of that parent, or parent.prepend(newElement) to put it at the very beginning.



ques-3 : Event Bubbling is a type of event propagation in the HTML DOM. When an event (like a click) happens on an element, that event first runs the handlers on that specific           element, then on its parent, then all the way up to other ancestors. 

 The event starts at the specific element you interacted with (the target). then the event  "bubbles" up the DOM tree and If any of those parent elements have an event listener for that same event, those listeners will also be triggered.



ques-4 : Event Delegation in JavaScript is an approach where, rather than attaching an event listener to each of the child elements, an event listener is added to one parent element. So, when any child element is clicked, the event bubbles up to the parent element, and then the event is handled by the parent element. This approach is advantageous because it increases performance, reduces memory usage, and is applied to all child elements, even newly added ones.


ques -5 : preventDefault() and stopPropagation() are both methods of events in JavaScript programming, but they are used differently.
          
         The preventDefault() method prevents the browser’s default action from happening for the current event. For instance, it can be used to stop a form from submitting or  a link from being clicked.
         
        The stopPropagation() method prevents the event from moving or bubbling up to other parent elements.