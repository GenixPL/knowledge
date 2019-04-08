#### Bucket sort (with insertion sort): [(link)][1] [(link)][2]
* Best Time Complexity: **O(n)**. 
    Best case occurs when number of buckets ~ array size.

* Average Time Complexity: **O(n + n^2/k +k)**, where k is the number 
    of buckets

* Worst Time Complexity: **O(n * 2)**. When there is only one bucket or every 
    thing is in one bucket.

* Auxiliary Space: **O(k)**.

* Application: 
    * Bucket sort is mainly useful when input is uniformly distributed over a range

    * Trades RAM for speed

[1]: https://www.geeksforgeeks.org/bucket-sort-2/
[2]: https://en.wikipedia.org/wiki/Bucket_sort