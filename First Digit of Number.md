## 01. First Digit of Number

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/first-digit-of-a-number/1)

### Problem Description

**Task:** Given a number n, find the first digit of the number.Examples:Input: n = 123

#### Examples

##### Example 1

- **Output:**
```text
1
```

##### Example 2

- **Input:**
```text
n = 976
```
- **Output:**
```text
9
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(log n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-13 19:44:20
- **Status:** Correct
- **Marks:** 2

```cpp
class Solution {
  public:
    int firstDigit(int n) {
        // code here
        while(n>=10){
            n/=10;
        }
        return n;
    }
};
```

*Generated on: 13/11/2026, 19:44:53*