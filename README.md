Download Link: https://assignmentchef.com/product/solved-initialize-an-array-of-50-numbers-in-memory
<br>
Your task is to write assembly code to initialize an array of 50 numbers in memory. Each number of the array should be a multiple of the first number ‘x’ (where 1 &lt;= x &lt;= 10). For example if x=5, the array should be {5, 10, 15, 20, 25, … , 245, 250}. Once the array is initialized, the next task is to search for a number ‘y’ in the array using ‘Binary Search’ algorithm. The way Binary Search algorithm works is following: Input: Sorted array of numbers; Number to be searched called ‘y’1. Calculate the midpoint index of the array by taking mean of the index of the first and the lastarray elements. The element at mid-point index is called ‘m’.

2. If the element at the midpoint index is the desired element, the search stops by returning theindex of the desired element.

3. If m is greater than y ignore the part of the array after m (including m) for further search. If mis less than y ignore the part of the array before m (including m) for further search.

4. In any case, repeat steps 1, 2, and 3 on the remaining elements of the array. Continue till anelement is found or the array indexes to be searched are exhausted.