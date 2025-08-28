1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
i) getElementById means it only select a single element matching with the id name.
ii) getElementsByClassName means it select all element with a matching class name. It is helpful to do same work for multiple section.
iii)querySelector / querySelectorAll : querySelector means it will select the CSS selector with which first element matches. querySelectorAll means it will select all element which matches with CSS selector.


2.How do you create and insert a new element into the DOM?
To create a new element --> document.createElement('tag-name')
To insert a new element --> parent.appendChild()


3.What is Event Bubbling and how does it work?
When a event happens on an element, it first runs on that element and then bubble up to its parent.
Suppose I have a div element that contains a button. If I click on that button an event will triggered on that button then same event will also triggered on the div element.


4.What is Event Delegation in JavaScript? Why is it useful?
Instead of adding eventListener to multiple child element add one eventListener to parent element is Event Delegation.

i--> It is less time consuming
ii--> It improves performance
iii--> It also works for dynamically added elements


5.What is the difference between preventDefault() and stopPropagation() methods?
The preventDefault() is used to prevent the browser default behavior for any event.
The stopPropagation() is used to stop the event from bubbling to its parent.