## 01. Odd or Even

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/odd-or-even3618/1?selectedLang=cpp)

### Problem Description

**Task:** Given a positive integer n, find if it is odd or even. Return true if the number is even else false.Examples:Input: n = 15

#### Examples

##### Example 1

- **Output:**
```text
false
```
- **Explanation:** The number is not divisible by 2, Odd number.Input: n = 44Output: trueExplanation: The number is divisible by 2, Even number.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-18 20:14:32
- **Status:** Correct
- **Marks:** 2

```cpp
class Solution {
  public:
    bool isEven(int n) {
        // code here
        if((n/2)*2==n){return 1;}
        else{return 0;}
    }
};
```

*Generated on: 18/11/2026, 20:14:56*