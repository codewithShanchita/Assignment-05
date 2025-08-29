1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans:

getElementById("id") → Gets one element by its id.

getElementsByClassName("class") → Gets many elements with the same class.

querySelector("selector") → Gets the first element that matches a CSS rule (#id, .class, tag).

querySelectorAll("selector") → Gets all elements that match a CSS rule.


2. How do you create and insert a new element into the DOM?

Ans:

Create element: - document.createElement('tagName')

Insert element: - appendChild() prepend() innerHTML


3. What is Event Bubbling and how does it work?

Ans:

Event Bubbling means when an event happens on an element, it first runs on that element, then it goes upwards to its parent, grandparent, and so on until the root.

How it works:

If you click a button inside a div, first the button’s click works, then the div’s click, then the body’s click.


4. What is Event Delegation in JavaScript? Why is it useful?

Ans:

Event Delegation is when we put an event on a parent element to handle events of its child elements using bubbling.
It is useful because it saves memory, makes code simple, and works for new child elements too.


5. What is the difference between preventDefault() and stopPropagation() methods?

Ans:

preventDefault() → Stops the browser’s default action (like stopping a form from submitting or a link from opening).

stopPropagation() → Stops the event from bubbling up to parent elements.