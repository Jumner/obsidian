# Linked Lists
---
![[Pasted image 20220105124344.png]]

## A linked list is a method that allows a list of unknown size to be stored in the heap.
If the list is known at compile time, it can be stored sequentially and added to the **[[The Stack and the Heap#Stack|Stack]]** or a section of the **[[The Stack and the Heap#Heap|Heap]]** can be found that is large enough

If it is not known at compile time, a **linked list** can be used. Each element is scattered through the **[[The Stack and the Heap#Heap|Heap]]** and each element stores its value plus a pointer to the next number. 

Requires overhead because the pointer trail must be followed whenever data is accessed or modified.

The last element has a **nullptr** to tell the computer that there is no following value