# Technical-Interview

Efficiencty: Time Efficiency (imp) and Space Efficiency.

Big O notation:
- roughly equals no. of lines of code.
- equals no of times loops run.

General Representations:
O(1) ~ O(5) ~ O(10)
O(n) ~ O(5n) ~ O(10n + 10)
O(n^2) ~ O(4n^2 + 7)

Collections:
- collection or lists of items
- does not have any fixed order

Lists:
- ordered collections

Arrays:
- lists with indices for each item
- adding and removing can be difficult O(n)
- access and search is easy O(1)

Linked Lists
- lists where each element is linked to its successive element
- adding and removing is easy than arrays
- stores address of the next element
- when adding new item at the back of one element, at first add the memory address of the successive element in the new element, then add address of new element to the actual element
- when deleting item, at first assign the address of successive element to the previous element.

Double Linked Lists:
- similar to the Linked List but stores both previous and next element address in each element


Binary Search:
search by dividing the array in half

Recursive Function:
Base Case :- Exit Condition
Recursion :- Calling the self function

Bubble Sort:
- Iterate thorugh the array and switch consecutive elements for sorting

Merge Sort:
- Divide the array into multile arrays with merge these arrays step by step by sorting each one

Quick Sort:
- Select a pivot value
- move values less than pivot to left and greater than pivot to right

Binary Search Tree:
- Tree which have maximum of 2 child nodes
- No element is repeated
- Smaller value lies on left side while larger value lies on right side

Heaps:
- Special Trees where parent is always either smaller or larger than the children
- Max heap if parent is larger and Min heap if parent is smaller than the children
