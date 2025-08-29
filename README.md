What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Answer : The difference between getElementBYId, getElementsByClassName, querySelector and querySeletorAll is 
1. getElementById fetch the element from html file targeting the specified ID
2. getElementsByClassName fetch all the elements which have the same classes. So it fetch an array like object
3. querySelector fetch only the first HTML element of the specific CSS selector
4. querySelectorAll fetch all the items of HTML element of the specific CSS selector.

How do you create and insert a new element into the DOM?

Answer : Process of creating and inserting a new element into the DOM 
1. let newElement = document.createElement('element name');
2. newElement.innerText = 'text';
3. Now fetch the element by ID where you want to create the element and save it in a variable
4. Use the Variable to appendChild the newElement.

What is Event Bubbling and how does it work?

Answer : Event bubbling means if I click an element it will also be clicked on it's parent along with the body tag and the entire document.
To put It simply if I kill you it will affect your parents, family, grandparents and their parents (If they were alive).

What is Event Delegation in JavaScript? Why is it useful?
It simply means that en event is always bubbled up to the parent element so instead of using eventListener to every child element we can just add 
it too the parent and he will know which child has gone through an event.

What is the difference between preventDefault() and stopPropagation() methods?

Answer : The preventDefault() does not stop bubbling the event rather it just stops the default browser behaviour but 
when we use stopPropagation() it stops even the bubbling of the event.
