PURPOSE
-------


The purpose of the code is to demonstrate the Stooge Sort algorithm's sorting capabilities. Stooge Sort is a recursive sorting algorithm that works by dividing the array into three parts, recursively sorting the first and last two-thirds, and then recursively sorting the first two-thirds again. While it's not an efficient sorting algorithm for practical use, it's useful for educational purposes to understand recursive sorting.

WORKING
-------

The N variable represents the number of elements in the array to be sorted (in this case, 5), and the sequence array holds the integers to be sorted.

The stoogeSort function is the core of the algorithm. It takes three parameters: the array L, the start index i, and the end index j. These parameters define the subarray to be sorted.

If the element at index j is smaller than the element at index i, they are swapped to ensure that the subarray is in non-decreasing order.

If the size of the subarray (j - i + 1) is greater than or equal to 3, the Stooge Sort algorithm is recursively applied to the following three parts:

The first two-thirds of the array.
The last two-thirds of the array.
The first two-thirds of the array again.
The printSequence function is a helper function used to print the elements of an array.

In the main function, a sequence of random integers is generated and stored in the sequence array.

The original sequence is printed.

The stoogeSort function is called to sort the sequence.

The sorted sequence is printed.

Here's how the code works in practice:
--------------------------------------

Random integers are generated and stored in the sequence array.
The original sequence is printed.
The stoogeSort function is called to sort the sequence array.
The sorted sequence is printed.
The Stooge Sort algorithm recursively divides the array and sorts it, ensuring that the elements are in non-decreasing order. While it's not efficient for large arrays, it serves as a simple example of a recursive sorting algorithm.
