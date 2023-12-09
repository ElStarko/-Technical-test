Assuming...
list = [5, 4, 5, 4, 5, 4, 4, 5, 3, 3, 2, 2, 2, 1, 5]
n = 2
Count the number of times each item appears in the list
counts ==> { 1: 1, 2: 3, 3: 2, 4: 4, 5: 5 }
Object.entries(counts)  ==> [ [ '1', 1 ], [ '2', 3 ], [ '3', 2 ], [ '4', 4 ], [ '5', 5 ] ]
a ==>  [ '1', 1 ], b => [ '2', 3 ], ...until the last a and b..., a ==> [ '4', 4 ], b ==> [ '5', 5 ]
a[1] ==> 1, b[1] ==> 3 // indexed the 2nd element of a and b for all a and b, and sort them in the process
sorted ==> [ [ '1', 1 ], [ '3', 2 ], [ '2', 3 ], [ '4', 4 ], [ '5', 5 ] ]
n - 1 ==> nth item in the array
sorted[n - 1][0] ==> sorted[nth][0] => sorted[nth][0]
if nth ==> 2, then sorted[1] ==> [ '3', 2 ]
sorted[1][0] ==> 3 which is the nthRarestElement
To make sure that the nthRarestElement, n is not out of bounds;
if n is greater than the total number of items in the sorted list,
total number of items in the sorted list is used instead of n
if n is less than or equal to 0, 0 is used instead of n
otherwise, n is used.
