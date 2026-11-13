## 01. Decision Making

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/decision-making/1)

### Problem Description

**Task:** Given two integers, n and m. The task is to check the relation between n and m. Print "less" if n < m, "equal" if n = = m, and "greater" if n > m.Examples : Input: n = 4, m = 8

#### Examples

##### Example 1

- **Output:**
```text
greater
```
- **Explanation:** 8 > 4 so print 'greater'.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-13 19:55:14
- **Status:** Correct
- **Marks:** 1

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, m;
    cin >> n >> m;
    if(n<m){cout<<"less";}
    else if(n>m){cout<<"greater";}
    else{cout<<"equal";}

    // code here
    

    return 0;
}
```

*Generated on: 13/11/2026, 19:55:43*