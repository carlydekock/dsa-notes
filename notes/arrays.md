# Arrays

- If sorted or partially sorted -> keep **binary search** in mind
- Subarray problems indicate the **sliding window** technique
- If you have two arrays to process -> common to have an index **pointer** per array
- If you can sort the array, sometimes it simplifies the problem significantly
- When sorting, be sure the order of elements doesn't matter
- Grid problems, represented as an array of arrays (sudoku, tic tac toe, word search type problems)
- Can traverse the array more than once, and still have O(n) runtime

## Sorting Algos

- Elementary sorting algorithms: insertion sort, selection sort, bubble sort
- Intermediate sorting algorithms: quick sort, merge sort
- Other common ones: counting sort, radix sort, bucket sort

## Resources

- [Tech interview handbook](https://techinterviewhandbook.org/algorithms/array/) notes and example array questions
- [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

## Things to Remember

- To fill an array with 0's as placeholders: ```Array.from({length: 10}, () => 0)```
- shift: removes element from front of array
- unshift: add one or more elements to start of the array
- push: add to the end
- pop: remove from the end
- slice: copies part of an array and returns it, does not mutate the original
- splice: mutates array by adding or removing elements
- indexOf: returns **first** index which given value is found, or -1 if value is not found
- Built in sort function: ```arr.sort((a, b) => a-b)``` will sort ascending, and ```arr.sort((a,b) => b-a)``` will sort descending

## Patterns

- Pointer(s)
- Sliding window
