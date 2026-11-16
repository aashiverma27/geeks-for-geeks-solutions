## 01. Data Types

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/data-types/1)

### Problem Description

**Task:** Given a program template, declare four variables named a, b, c, and d with the data types int, float, double, and long long respectively inside the required scope. Example:Input: None

#### Examples

##### Example 1

- **Output:**
```text
verified
```
- **Explanation:** All 4 variables are declared with proper data type.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-16 15:09:36
- **Status:** Correct
- **Marks:** 2

```cpp
#include <iostream>
#include <typeinfo>
using namespace std;

int main() {int a;float b;double c; long long d;
    
    // Code here to declare the variables


    // Variables declaration checking (Please do not change)
    if ((typeid(a) == typeid(int)) and (typeid(b) == typeid(float)) and
        (typeid(c) == typeid(double)) and (typeid(d) == typeid(long long)))
        cout << "verified\n";

    return 0;
}
```

*Generated on: 16/11/2026, 15:10:01*