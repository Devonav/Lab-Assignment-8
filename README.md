# Merge Sort Implementation

This program implements the merge sort algorithm in C. Merge sort is a popular sorting algorithm known for its efficiency and stability. It follows the divide and conquer strategy to sort arrays efficiently.

## Features

- Implements the merge sort algorithm.
- Memory allocation and deallocation managed using custom `Alloc` and `DeAlloc` functions, ensuring compliance with specific requirements.
- Parses input data from files and sorts the data using merge sort.
- Prints runtime and extra memory allocated during sorting.
- Utilizes a custom `printArray` function to print the first and last 100 elements of the sorted array.

## How to Use

1. Clone the repository or download the source code.
2. Compile the program using a C compiler (e.g., GCC).
3. Run the compiled executable.
4. The program will read input data from provided input files, sort the data using merge sort, and print runtime and memory usage information along with the sorted arrays.

## File Structure

- `main.c`: Main source code file containing the implementation of merge sort, memory allocation functions, parsing functions, and the main function.
- `input1.txt`, `input2.txt`, `input3.txt`, `input4.txt`: Input files containing unsorted data to be sorted using merge sort.
- `README.md`: This README file providing information about the program.

## Requirements

- C compiler (e.g., GCC) to compile the source code.

## Note

- This program follows specific guidelines, including the use of custom memory allocation functions (`Alloc` and `DeAlloc`) and a custom `printArray` function.
- Please ensure that the input files contain integer values separated by spaces or newline characters.

