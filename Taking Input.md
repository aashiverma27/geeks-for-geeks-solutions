## 01. Taking Input

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/taking-input/1)

### Problem Description

**Task:** You need to perform three separate tasks based on the given input:
String Input and Print: Read a string s (which may contain spaces) and print it as it is.
Integer Input and Print: Read an integer n and print it without any change.
Float Input and floor Print: Read a floating-point number as input, take its floor value, and print as an integer.

#### Examples

##### Example 1

- **Input:**
```text
s = "Hello", n = 20, f = 5.5Output: Hello 20 5Explanation: The string Hello is printed as it is. The integer 20 is printed without any change.For floating-point number 5.5, its floor value 5 is printed.
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (2)

#### Solution 1 (C++)

- **Submitted:** 2026-11-12 14:59:29
- **Status:** Correct
- **Marks:** 0

```cpp
#include <iostream>
#include <string> 
#include <cmath>
using namespace std;

int main() {
    string s;
    int n;
    float f;
    int ff; // To Store floor of float variable f

    // code here
    getline(cin,s);
    cin>>n;
    cin>>f;
    ff=floor(f);

    cout << s << endl;
    cout << n << endl;
    cout << ff << endl;
    return 0;
}
```

#### Solution 2 (C++)

- **Submitted:** 2026-11-12 14:59:26
- **Status:** Correct
- **Marks:** 1

```cpp
#include <iostream>
#include <string> 
#include <cmath>
using namespace std;

int main() {
    string s;
    int n;
    float f;
    int ff; // To Store floor of float variable f

    // code here
    getline(cin,s);
    cin>>n;
    cin>>f;
    ff=floor(f);

    cout << s << endl;
    cout << n << endl;
    cout << ff << endl;
    return 0;
}
```

*Generated on: 12/11/2026, 15:00:15*