## 01. Print With Space

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/print-with-space/1)

### Problem Description

**Task:** Given two strings a and b, print them on the same line with a single space between them. Print a newline after the output.

#### Examples

##### Example 1

- **Input:**
```text
a = "Hello", b = "World"
```
- **Output:**
```text
Hello World
```
- **Explanation:** a and b are printed in a single line and a space separates them.

##### Example 2

- **Input:**
```text
a = "Geeks", b = "for"
```
- **Output:**
```text
Geeks for
```
- **Explanation:** a and b are printed in a single line and a space separates them.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-15 20:52:44
- **Status:** Correct
- **Marks:** 1

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    string a, b;
    cin >> a >> b;
    cout<<a<<" "<<b;

    // code here
    

    return 0;
}
```

*Generated on: 15/11/2026, 20:53:11*