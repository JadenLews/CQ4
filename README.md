# CQ4
The issue with the correctness invariant question is that the while loop did not include j = 0. That is why it would return the array with all elements sorted except for the first one. 
Runtime- For this problem, there is a for loop for each element in the array, so there is at least a run time of n. For each iteration of the for loop there is a while loop from j = i to j = 0. This is a n(n+1)/2 which means the runtime is O(n^2)
Space- If you exclude the input array, the code makes a variable for "value" and int j. These values are changed each iteration of the forloop but are a constant amount of storage used for any input. So the space used is constant, so O(1)

CamelCase
Runtime- This program iterates through each character of the input word which makes the runtime O(n)
Space- The additional space used for this program is an integer storing the amount of words, and a character for iteration. This is a constant amount of variables no matter the input size. Size is constant, O(1)
