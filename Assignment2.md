

problem 1

The Big O for this algorithm is O(n²) The while loop goes through an array and compares the pairs of elements 
and as the size of the array gets bigger the amount of comparisons gets bigger too by about n times n.

T(n) = n²

So the final answer is:

Big O = O(n²)



problme 2

First I would number the bags from 1 to 20
I would take 1 M&M from bag 1, 2 from bag 2, 3 from bag 3, and keep going until I take 20 M&Ms from bag 20
If all the M&Ms weighed 1 gram, the total should be

1 + 2 + 3 + ... + 20 = 210 grams

I would then put all of the M&Ms I took on the scale at the same time
Since the heavier M&Ms weigh 0.1 grams extra, the amount over 210 grams tells me which bag is the heavy bag
For example, if the scale says 210.7 grams, then bag 7 is the heavy bag
