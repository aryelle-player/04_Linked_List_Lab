04_Linked_List_Lab
==================

Implement a simple linked list using pointers and classes.

Requirements
------------

1. Add, remove, get, and set should be O(1) if `i == 0` or if `i == size()-1`
2. Add, remove, get, and set should throw a string exception if `i >= size()`. Find should throw a string exception if `i > size()`
3. Do not leak memory (make sure remove and the destructor do the right thing)
4. `size()` is O(1) time (keep track of the numItems when you add or remove, so you can just return the variable)

Reading
=======
"Open Data Structures," Chapter 3, up through section 2 (DLList), http://opendatastructures.org/ods-cpp/3_Linked_Lists.html

Questions
=========

#### 1. Which of the above requirements work, and which do not? For each requirement, write a brief response.

1. these methods all work
2. all exceptions are thrown
3. remove and destructor work properly I believe
4. size works properly due to constant updating

#### 2. If we did an ArrayList instead of a LinkedList, which of the public methods would be faster, and which would be slower? Explain your answer.

the get and set methods would be faster. with a linked list, it take linear time to do these methods and constant time with an arraylist because "Arrays offer constant time access to any value in the array"

#### 3. What is one question that confused you about this excercise, or one piece of advice you would share with students next semester?
determining the time a function will take is still a bit foggy
