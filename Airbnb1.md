## Airbnb interview questions

## Question 1: reverse function
- using String would be O(n*n) since string is immutable. Each time is creating a copy of that.

## missing item list difference
- find_missing([4,12,9,5,6], [4,9,12,6]) => 5
### Solution 1:
- create two sets and compare difference time: O(n) +O(m)

### Solution 2:
- sort ? nlgn heap

### Solution 3:
- sum(a)-sum(b) 
-----------------------------------------------------------------
- improve this by using xor since sum(a) may be large
-- xor: same value will yiled 0, different value will yield 1. 
-- So same values do xor operation are 0. Here Xor_sum is mising 
-- value
-----------------------------------------------------------------

## reference
- interview.io
