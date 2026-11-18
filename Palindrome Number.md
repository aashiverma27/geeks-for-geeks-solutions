## 01. Palindrome Number

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/palindrome0746/1?selectedLang=cpp)

### Problem Description

**Task:** You are given an integer n. Your task is to find if it is a palindrome. Examples:Input: n = 555

#### Examples

##### Example 1

- **Output:**
```text
trueExplanation: if number is palindrome, mainly ignore sign.
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(d), d is number of digits in nAuxiliary Space: O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-18 20:05:38
- **Status:** Correct
- **Marks:** 2

```cpp
class Solution {
  public:
    bool isPalindrome(int n) {int a=n;long long ans=0;long rem=0;
        while(n!=0){rem=n%10;
        ans=ans*10+rem;
            n/=10;
        }
        return ans==a;
        // code here
    }
};
```

*Generated on: 18/11/2026, 20:06:03*