## 01. Swap Two Numbers

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/swap-the-numbers/1)

### Problem Description

**Task:** Given two numbers a and b, you need to swap their values so a holds the value of b and b holds the value of a.Examples :Input: a = 1 b = 2

#### Examples

##### Example 1

- **Output:**
```text
2 1
```
- **Explanation:** Initially a = 1 and b = 2, now a = 2 and b = 1.

##### Example 2

- **Input:**
```text
a = 6 b = 7 Output: 7 6
```
- **Explanation:** Initially a = 6 and b = 7, now a = 7 and b = 6.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-13 19:57:01
- **Status:** Correct
- **Marks:** 1

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;

    // code here
    a=a+b;
    b=a-b;
    a=a-b;

    cout << a << " " << b;
    return 0;
}
```

*Generated on: 13/11/2026, 19:57:31*