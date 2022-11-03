# INSERTION SORT METHOD

### [22,27,16,2,18,6] -> Insertion Sort

> [16,22,27,2,18,6], [2,16,22,27,18,6], [2,16,18,22,27,6], [2,6,16,18,22,27]
> Big O Notation --> O(1)

### Time Complexity of Insertion Sort

> AVG CASE: Six elements x five possible shifting on average / 2 cuz we assume, on average, half of the elements have already been sorted / 2 again cuz the element soon to be sorted will have to be moved to middle of already sorted elements --> 7,5
> In other words, n x (n - 1) x 1/4 which also equals to 1/4n^2 - 1/4n
> O(n^2)

> WORST CASE: Same as in AVG CASE except for the fact that there is a possibility an element will have to be sorted to beginning of the array. That's why 6 x 5 x 1/2
> In other words, n x (n - 1) x 1/2
> O(n^2) again.

> BEST CASE: Perfect sceneario since if all the elements are in ideal order, there will be only one comparison operation and will be no transferring at all. Therefore, n-1 is all.
> O(n)

### If sorted, which case the number 18 belongs to?

> [2,6,16,18,22,27] --> Number 18 is right at the middle so AVG case it is.

### [7,3,5,8,2,9,4,15,6] Sort this array for the first 4 sorting.

> [3,7,5,8,2,9,4,15,6], [3,5,7,8,2,9,4,15,6], [3,5,7,8,2,9,4,15,6], [2,3,5,7,8,9,4,15,6]
