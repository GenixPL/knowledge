###### Bubble sort: [(link)][1]
* Worst and Average Time Complexity: **O(n * n)**. 
    Worst case occurs when array is reverse sorted.
* Best Case Time Complexity: **O(n)**. 
    Best case occurs when array is already sorted.
* Auxiliary Space: **O(1)**. 
    (Sorts in place)
* Possible optimizations: 
    * Stopping the algorithm if inner loop did not cause any swap.
* Application: 
    * In computer graphics it is popular for its capability to detect
        a very small error (like swap of just two elements) in 
        almost-sorted arrays and fix it with just linear complexity (2n).

[1]: https://www.tutorialspoint.com/data_structures_algorithms/bubble_sort_algorithm.htm
