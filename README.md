Write a C program that finds the starting index of one array within another array.

Define a function findArrIndex that takes four parameters: two integer pointers representing the arrays to search (array1 and array2), and two integers representing the sizes of these arrays (size1 and size2).
Within the function, use pointer arithmetic to iterate over array2 and compare its elements with the elements of array1.
If array1 is found as a contiguous subarray within array2, return the starting index of array1 within array2.
If array1 is not found as a contiguous subarray within array2, return 0.
In the main function, test the findArrIndex function with different pairs of arrays and print the results to the console.
Ensure that the program properly handles arrays of different sizes and that it returns the correct starting index or 0 based on the presence of array1 within array2.
