## 01. Print With Separator

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/print-with-separator/1)

### Problem Description

**Task:** Given two strings s1 and s2, and a separator symbol separator, print s1 and s2 with separator between them, followed by a new line.Examples :Input: s1 = "Hello", s2 = "World", separator = "@"

#### Examples

##### Example 1

- **Output:**
```text
Geeks-ForExplanation: s1 and s2 are printed with the - symbol in between.
```
- **Explanation:** s1 and s2 are printed with the @ symbol in between.Input: s1 = "Geeks", s2 = "For", separator = "-"

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-17 19:37:03
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>

using namespace std;

int main() {

    string s1, s2, separator;
    cin >> s1 >> s2 >> separator;

    // code here
    cout<<s1<<separator<<s2;

    return 0;
}
```

*Generated on: 17/11/2026, 19:37:37*