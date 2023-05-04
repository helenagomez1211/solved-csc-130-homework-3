Download Link: https://assignmentchef.com/product/solved-csc-130-homework-3
<br>
In this assignment you’ll get more practice with stacks and queues.  You will also practice testing your code for edge cases.

<h1>MyStack.java</h1>

Implement a stack using linked lists data structure.  Implement your own linked list.  <strong><u>You</u> <u>cannot use Java’s java.util.LinkedList.</u></strong>

<ul>

 <li>pop(): returns and removes the last value on the stack</li>

 <li>push(String item): Push a given value onto the stack</li>

 <li>isEmpty(): returns true or false depending on if the stack is empty</li>

 <li>printStack(): prints the items on the stack to console</li>

 <li>Handles errors for all possible edge cases (i.e. doesn’t throw an unhandled exception to the user)</li>

 <li>MyStack(String[] list): constructor which creates the stack with the items in list on the stack. So if list had {“a”, “b”, “c”} the stack would look like: “c” on top of “b” on top of “a.”</li>

</ul>




<h1>MyQueue.java</h1>

Implement a queue using the MyStack.java implementation as your data structure.  <strong>In other words, your instance variable to hold the queue items will be a MyStack class.</strong>

<ul>

 <li>enqueue(String item): inserts item into the queue</li>

 <li>dequeue(): returns and deletes the first element in the queue</li>

 <li>isEmpty(): returns true or false depending on if the queue is empty</li>

 <li>printQueue(): prints the items in the queue to console</li>

 <li>MyQueue(String[] list): constructor which creates the queue with the items in list in the queue: So if list had {“a”, “b”, “c”} the queue would look like: “a” first, then “b”, then “c.”</li>

</ul>




<h1>MyTest.java</h1>

<ul>

 <li>You can have other methods in this class but will be graded to have a:</li>

 <li>Main method which tests every method you implemented above in MyStack and MyQueue.</li>

 <li>As you test the methods, print to console (1) what you are testing, (2) what value you are expecting, (3) whether your test passed or failed.</li>

 <li>Test for edge cases and clearly state in your comment/print out which edge case you’re testing.</li>

</ul>


