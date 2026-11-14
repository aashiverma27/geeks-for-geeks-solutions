## 01. Switch Statement

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/switch-statement/1)

### Problem Description

**Task:** Given a number n, use a switch statement to print "Stop" if the given number is 1 (or Red light)"Standby" if the number is 2 (Yellow light)"Go" if the number is 3 (Green light). For any other number, print "Unknown" (without quotes).Examples:Input: n = 1

#### Examples

##### Example 1

- **Output:**
```text
Unknown
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-14 17:58:53
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;

    // code here
    switch(n){
        case 1:
        cout<<"Stop";
        break;
        case 2:
        cout<<"Standby";
        break;
        case 3:
        cout<<"Go";
        break;
        default:
        cout<<"Unknown";
    }

    return 0;
}
```

*Generated on: 14/11/2026, 17:59:22*