Download Link: https://assignmentchef.com/product/solved-concrete-linkedlist-class
<br>
Create concrete LinkedList class that extends the provided ALinkedList class. You will need to override the extractmethod in your class. You can use your main method for testing your method (although you do not need to provide a main method).concrete LinkedList class that extends the provided ALinkedList class. You will need to override the extractmethod in your class. You can use your main method for testing your method (although you do not need to provide a main method).

Recall that a list is an ordered collection of data

<pre class="ql-syntax">X_0, X_1, X_2, ..., X_n</pre>

The extract(int start, int end) method removes all elements

<pre class="ql-syntax">X_start, X_start_1, ..., X_end-1</pre>

from the list. It also returns all removed elements as a new list (LinkedList) that retains the same ordering.

For example, if the initial list called animals was

<pre class="ql-syntax">cat, dog, eel, cow, owl, pig, pip</pre>

then animals.extract(1,5) would return the new list

<pre class="ql-syntax">dog, eel, cow, owl</pre>

and animals would now be the list

<pre class="ql-syntax">cat, pig, pip</pre>