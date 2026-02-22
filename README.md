1...What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans : 
getElementById : its used to select any element by ID(unique),it returns one element and it is defined as " # "

getElementsByClassName : its used to select any element by class name,it returns lits and it is defined as " . "

querySelector : its use css selector and it is define as "#"(id),"."(class) also return first matching element .

querySelectorAll : its return nodelists.



2....How do you create and insert a new element into the DOM?
answer : 
1. create  element using document.createElement() 
2. then using innerText to add content
3. then use appendChild(), append() etc. to insert it



3...What is Event Bubbling? And how does it work?

Answer :
Event Bubbling is a process where an event starts from the target element and then moves upward to its parent elements.
If i click on the child, event first happens on the child ,then moves to the parents and then go to the grandparent  then  its repeatedly  do the same thing when it reaches the document.


4...What is Event Delegation in JavaScript? Why is it useful?

Answer : 
Event Delegation is a technique where we add an event listener to a parent element instead of adding event listeners to many child elements.

Useful:
1.good performance
2.save memory
3. short code

5... What is the difference between preventDefault() and stopPropagation() methods?

Answer :

The main difference is  preventDefault() stops the browser’s default action, while stopPropagation() stops the event from bubbling to parent elements.
preventDefault() controls what the browser does, while stopPropagation() controls how the event moves through the DOM tree.