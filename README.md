# Insertion Sort in C

This repository contains an implementation of the Insertion Sort algorithm in C. Insertion Sort is a simple sorting algorithm that builds the final sorted array one item at a time. It is suitable for small data sets and is much less efficient on large lists than other sorting algorithms, such as QuickSort, MergeSort, or HeapSort.

## Overview of Functions

1. `void insertion_sort(int arr[], int n)`: This function takes an integer array `arr` of size `n` as input and sorts it using the Insertion Sort algorithm.

2. `void print_array(int arr[], int size)`: This function takes an integer array `arr` and its size as input, and prints the elements of the array.

## Sample Usage and Output

Here is an example of how to use the Insertion Sort implementation with an integer array:

```c
int main() {
    int arr[] = {12, 11, 13, 5, 6};
    int n = sizeof(arr) / sizeof(arr[0]);

    printf("Original array:\n");
    print_array(arr, n);

    insertion_sort(arr, n);

    printf("Sorted array:\n");
    print_array(arr, n);

    return 0;
}
```

## Output

```
Original array:
12 11 13 5 6
Sorted array:
5 6 11 12 13
```
