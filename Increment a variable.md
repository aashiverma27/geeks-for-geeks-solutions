## 01. Increment a variable

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/increment-a-variable/1)

### Problem Description

**Task:** Given a pointer to the variable a, complete the function updateVar(a) so that it increases the value of the variable by 10. The function should not return anything.Examples : Input: a = 4

#### Examples

##### Example 1

- **Output:**
```text
14
```

##### Example 2

- **Input:**
```text
a = 61
```
- **Output:**
```text
71
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-15 21:00:42
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    void updateVar(int *a) {
        // code here
        *a=*a+10;
        
    }
};
```

*Generated on: 15/11/2026, 21:01:10*