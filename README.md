# Selection-Sort-Visualiser
A visualization of the most common used sorting algorithm.
The human brain can easily process visuals in spite of long codes to understand the algorithms. In this article, Selection sort visualization has been implemented using graphics.h library. As we all know that bubble sort swaps the adjacent elements if they are unsorted and finally the larger one being shifted towards to the end of array in each pass. Sometimes, it becomes difficult to analyze the data manually, but after plotting graphically it is much easier to understand as shown in the figure below.
![alt text](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/02/bubble-sort1.png)
## Approach:

- Even comparing two types of data-set is also difficult with numbers if the size of the array is large.
- The graphical representation of randomly distributed numbers and reverse sorted numbers is shown below.
- The white line is used to represent the length of number (9 being represented by 9 pixels vertically upwards) while its position represents its index in the array.
- Graphically sorting can be shown simply by swapping the lines.
- As we swap the numbers in bubble sort, a different colour line can be used to see the current index in the array (here green colour).
- Here delay() can be increased to see the transition in the graph.
