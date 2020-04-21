# Sorting_Algo
All sorting related question

# 1.Bubble Sort
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order.
Optimized Implementation:
The above function always runs O(n^2) time even if the array is sorted. It can be optimized by stopping the algorithm if inner loop didn’t cause any swap
# Worst and Average Case Time Complexity:
O(n*n). Worst case occurs when array is reverse sorted.

# Best Case Time Complexity: 
O(n). Best case occurs when array is already sorted.

# Auxiliary Space: 
O(1)

# Boundary Cases: 
Bubble sort takes minimum time (Order of n) when elements are already sorted.

# Sorting In Place:
Yes

# Stable:
Yes
# Recursion Idea.
Base Case: If array size is 1, return.
Do One Pass of normal Bubble Sort. This pass fixes last element of current subarray.
Recur for all elements except last of current subarray

Due to its simplicity, bubble sort is often used to introduce the concept of a sorting algorithm.
In computer graphics it is popular for its capability to detect a very small error (like swap of just two elements) in almost-sorted arrays and fix it with just linear complexity (2n). For example, it is used in a polygon filling algorithm, where bounding lines are sorted by their x coordinate at a specific scan line (a line parallel to x axis) and with incrementing y their order changes (two elements are swapped) only at intersections of two lines
[bubble sort link](https://github.com/doyelsaha510/Sorting_Algo/blob/master/bubbleSort.java)
[recursive bubble sort link](https://github.com/doyelsaha510/Sorting_Algo/blob/master/bubbleSortRecur.java)
