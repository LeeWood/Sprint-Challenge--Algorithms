#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n log n)


c) O(n)

## Exercise II

Starting with the middle floor I would test if an egg would break when dropped. If the egg does NOT break at the middle point, then eliminate all the floors below the middle floor. After eliminating the floors lower than that middle point, repeat the process going half way up and then testing to see if the egg breaks from that point until we have a definite answer. This makes it so we don't have to test every floor, using a binaray search algorithm to find our answer. The runtime for this method would be O(log n).

