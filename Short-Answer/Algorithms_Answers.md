#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(N^2) because the loop is going over 
n^3 while the operation inside the loop is 
squaring n, which means it'll only loop 
n^2 times.

b) O(N) - the second for loop is 
exponential growth, which as the program 
scales it'll have an ever increasing 
diminishing effect which
makes it moot compared to the linear 
growth of the first for loop.

c) O(N) - Since the recursion will pop only
after it's completed, the 2 part doesn't 
matter, the recursion will still only run 
one time per bunnyEars passed in. which is
 O(N)

## Exercise II

We just need to figure out the
value of F, and eggs are our indicator, 
so a binary search would be best suited here, start at floor 0 and increase if 
egg doesn't break then set that is the 
minLimit, increase the floor 
exponentially until it breaks, then 
perform binary search between the two 
floors until a result is reached.

if egg != broken: go up one floor and throw again. else: set f to current floor