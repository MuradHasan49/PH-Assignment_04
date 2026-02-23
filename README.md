#All questions answered

1.Ans : getElementById Selects a single element by its unique id attribute value, and getElementsByClassName Selects all elements that have a specified class name or names. The class name is passed as a string without the . prefix, querySelector returns the first element that matches a specified CSS selector and querySelectorAll returns all elements that match the specified CSS selectors.

2.Ans : First Create the new element using the document.createElement() method then Add content or properties (like text, attributes, or classes) to the new element after adding Find the existing parent element and Insert the new element into the parent using appendChild(). This will add it as the last child of the parent element.

3.Ans : event bubbling is a phase in the browser's event flow where an event starts at the most specific element (the target) and then "bubbles" up through its ancestors in the DOM tree until it reaches the window. This means if you click a button nested inside a div, the click event first triggers the button's listeners, then the div's listeners, then the body's, and so on. 

4.Ans : Event Delegation is a technique where iam attach a single event listener to a parent element instead of adding individual listeners to every single child element. Because of "event bubbling," any click on a child element travels up to the parent, where the listener is waiting to catch it. iam then use event.target to figure out exactly which child was clicked.

5.Ans : preventDefault() stops the browser’s automatic action (like a link opening or a form refreshing), but the event still "bubbles" up to its parents. stopPropagation() does the opposite: it kills the event immediately, preventing it from reaching any parent elements, though the browser’s default action might still occur. Essentially, preventDefault() controls what happens, while stopPropagation() controls where the event travels.
