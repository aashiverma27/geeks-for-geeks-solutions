## 01. While Loop

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/while-loop/1)

### Problem Description

**Task:** Given a number n, print all numbers from 0 to n in increasing order in a single line using a while loop.Examples: Input: n = 3

#### Examples

##### Example 1

- **Output:**
```text
0 1 2 3
```
- **Explanation:** Numbers from 0 to 3 in increasing order are 0 1 2 3.Input: n = 5Output: 0 1 2 3 4 5Explanation: Numbers from 0 to 5 in increasing order are 0 1 2 3 4 5.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-12 15:10:21
- **Status:** Correct
- **Marks:** 1

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    int i=0;

    // code here
    while(i<=n){
        cout<<i<<' ';
        i++;
    }

    return 0;
}
```

*Generated on: 12/11/2026, 15:10:55*