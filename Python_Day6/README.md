Pancake Sort
Description
This is a Python implementation of the Pancake Sort algorithm. The algorithm sorts a list of integers by repeatedly flipping prefixes of the list to move the largest unsorted element to its correct position, similar to flipping pancakes in a stack.

During the sorting process, the code prints each flip operation showing the prefix length flipped and the current state of the array.

How It Works
Find the maximum element in the unsorted prefix.

Flip the prefix up to that maximum element to bring it to the front.

Flip the prefix up to the current unsorted size to move the maximum element to its correct sorted position.

Repeat until the entire list is sorted.
