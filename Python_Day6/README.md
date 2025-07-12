# Pancake Sort

Pancake Sort is a sorting algorithm that sorts a sequence by repeatedly flipping (reversing) prefixes of the list. The algorithm is inspired by the process of sorting pancakes in a stack with a spatula.

## How Pancake Sort Works

- Find the largest unsorted element in the array.
- Flip the array up to the position of this element to bring it to the front.
- Flip the entire unsorted portion to move the largest element to its correct position at the end.
- Repeat for the remaining unsorted portion.

## Time Complexity

- Worst Case: O(n²)
- Best Case: O(n²)
- Average Case: O(n²)

## Space Complexity

- O(1) (In-place sorting)


