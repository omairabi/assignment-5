### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
   Answer:getElementById means its returns a single element by its unique ID.
   getElementsByClassName means its returns a live HTMLCollection of elements matching a class.
   querySelector means returns its the first element matching a CSS selector.
   querySelectorAll means returns its a static NodeList of all elements matching a CSS selector.
2. How do you **create and insert a new element into the DOM**?
   Answer:createElement → setContent → appendChild

3. What is **Event Bubbling** and how does it work?
   Answer:event Bubbling is when an event starts from the target element and propagates upward through its ancestors in the DOM hierarchy.

4. What is **Event Delegation** in JavaScript? Why is it useful?
   Answer:Parent handles children’s events efficiently.

5. What is the difference between **preventDefault() and stopPropagation()** methods?
   Answer:preventDefault() blocks action, stopPropagation() stops bubbling.
