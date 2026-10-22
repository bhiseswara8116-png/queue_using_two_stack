# queue_using_two_stack

# Implementation of Queue Using Two Stacks

 1. Project Description

This is a Data Structures mini-project implemented in Python.
It demonstrates how to implement a Queue using two Stacks.

A Queue follows the FIFO (First In, First Out) principle,
while a Stack follows the LIFO (Last In, First Out) principle.

By using two stacks, we can perform queue operations such as
insertion, deletion, viewing the front element, and displaying
all elements.

 2. Objectives

- To understand the concepts of Stack and Queue.
- To implement a Queue using two Stacks.
- To perform enqueue and dequeue operations.
- To understand the FIFO principle.
- To analyze the time and space complexity of operations.

 3. Technologies Used

- Programming Language: Python 3
- Data Structure: Stack and Queue
- Editor: VS Code, IDLE, or any Python editor

 4. Features

- Enqueue: Insert an element into the queue.
- Dequeue: Remove the front element from the queue.
- Peek: View the front element without removing it.
- Display: Show all queue elements in FIFO order.
- Empty Queue Handling: Display a message when the queue is empty.
- Input Validation: Handle invalid menu choices and non-integer input.

 5. Project Files

queue-using-two-stacks/
|
|-- queue_using_two_stacks.py
|-- README.md

 6. How to Run the Project

Step 1: Install Python 3 on your computer.

Step 2: Save the source code as:
queue_using_two_stacks.py

Step 3: Open a terminal or command prompt in the project folder.

Step 4: Run the following command:

python queue_using_two_stacks.py

On some systems, use:

python3 queue_using_two_stacks.py

Step 5: Select an option from the menu and perform the
required queue operations.

 7. Algorithm

1. Initialize two empty stacks, Stack 1 and Stack 2.
2. For enqueue, push the new element into Stack 1.
3. For dequeue, check whether Stack 2 is empty.
4. If Stack 2 is empty, transfer all elements from Stack 1
   to Stack 2 by popping from Stack 1 and pushing into Stack 2.
5. If Stack 2 is not empty, remove its top element directly.
6. For peek, transfer elements if necessary and display the
   top element of Stack 2.
7. For display, show the elements of Stack 2 in reverse order,
   followed by the elements of Stack 1.
8. Repeat operations until the user selects Exit.

 8. Time Complexity

- Enqueue: O(1)
- Dequeue: O(1) amortized; O(n) worst case
- Peek: O(1) amortized; O(n) worst case
- Display: O(n)

Here, n represents the number of elements in the queue.

 9. Space Complexity

O(n), because the two stacks together store the queue elements.

 10. Conclusion

This project demonstrates the implementation of a Queue using
two Stacks in Python. It explains the difference between FIFO
and LIFO and shows how two stack data structures can work
together to perform queue operations efficiently.

