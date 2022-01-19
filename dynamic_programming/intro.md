DP
- systematically and efficiently explore all possible solutions.
- break down the problem into "overlapping subproblems"
- optimal substructure


Bottom-up (tabulation)
- iteration with base cases
	e.g. Fibonacci -> use F(0) and F(1) to calculate F(2)
- usually faster; iteration doesn't have the overhead
- typically implemented with nested for loops and an array

Top-down (memoization)
- recursion with memoization
	e.g. store (hashmap) the result and use it later
- typically implemented with a recursive function and hash map

When can we say it's a DP problem? 
First characteristic (either one of these)
- optimum value of something
- number of ways there to do something
e.g. minimum cost, maximum profit, longest possible, shortest way ...

Second characteristic
- later decisions depend on earlier decisions




DP framework 

State - set of variables that can identify a scenario 
These variables -> state variables

Combine 3 things
1. function/data structure that compute/contain the answer for every given state
2. recurrence relation to transition between states
3. base case for the recurrence relation not to go on infinitely
