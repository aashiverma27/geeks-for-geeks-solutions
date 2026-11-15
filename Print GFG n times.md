## 01. Print GFG n times

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/print-gfg-n-times/1)

### Problem Description

**Task:** Given a positive number n, print the string "GFG" exactly n times separated by a single space.Examples:Input: n = 5

#### Examples

##### Example 1

- **Output:**
```text
GFG GFG GFGExplanation: The string "GFG" is printed 3 times separated by spaces.
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-15 20:50:43
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    void printGfg(int n) {
        // code here
        for(int i=1;i<=n;i++){
            cout<<"GFG"<<" ";
        }
    }
};
```

*Generated on: 15/11/2026, 20:51:13*