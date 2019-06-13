## Google Interview Questions

### Edit distance
- insert, replace, remove
- dp

### Solution 1:
- Recursion
```java
m = len(str1)
n = len(str2)
//chekc from the last element
1. if(LastElement(str1)==LastElement(str2)) 
      return recursively call (m-1, n-1)
2. Else(not ssame), we consider all the operations on str1
      //insert: (m, n-1)
      //delete (m-1, n)
      //replace (m-1, n-1)
      return 1 + min((m, n-1), (m-1, n), (m-1, n-1));
```

### Solution 2:
- dp

### Reference
- Youtube video from intterview.io
- [Edit Distance GeekforGeeks](https://www.geeksforgeeks.org/edit-distance-dp-5/)
- [Leetcode 72 Edit Distance](https://leetcode.com/problems/edit-distance/)
