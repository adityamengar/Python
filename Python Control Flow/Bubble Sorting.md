# BUBBLE SORTING  

Bubble sort is a foundational, comparison-based sorting algorithm. It repeatedly steps through a list, compares adjacent elements, and swaps them if they are in the wrong order. The process repeats until the entire list is sorted  

## List Can Be Sorted In Two Ways:  
-> increasing (or more precisely ‒ non-decreasing) ‒ if in every pair of adjacent elements, the former element is not greater than the latter;  
-> decreasing (or more precisely ‒ non-increasing) ‒ if in every pair of adjacent elements, the former element is not less than the latter.  

-> the essence of this algorithm is simple: we compare the adjacent elements, and by swapping some of them, we achieve our goal.  

## Sorting a list:
We solve this issue in the following way: we introduce another variable; its task is to observe if any swap has been done during the pass or not; if there is no swap, then the list is already sorted, and nothing more has to be done. We create a variable named swapped, and we assign a value of False to it, to indicate that there are no swaps. Otherwise, it will be assigned True.