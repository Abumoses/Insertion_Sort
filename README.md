# Insertion Sort in C

This project implements the **Insertion Sort algorithm** using the C programming language. Insertion Sort is a simple and intuitive algorithm that builds the final sorted array one element at a time.

## What is Insertion Sort?

Insertion Sort works by:
- Taking elements from the unsorted part and inserting them into the correct position in the sorted part.
- It is similar to how you sort playing cards in your hand.

**Time Complexities:**
- Best Case (Already Sorted): O(n)
- Average Case: O(n²)
- Worst Case (Reversed Order): O(n²)

**Space Complexity:** O(1) (in-place sorting)

## Features

- Sort an array of integers in ascending order
- Displays the array before and after sorting
- Easy-to-understand, beginner-friendly C code

## Technologies Used

- **Language**: C
- **Compiler**: GCC (or any C compiler)
- **Libraries**: `stdio.h`

## How to Run

### 1. Compile the Program

```bash
gcc insertion_sort.c -o insertion_sort
