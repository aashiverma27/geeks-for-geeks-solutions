## 01. Even Odd Game

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/even-odd-game--153136/1)

### Problem Description

**Task:** Given a number n, number of apples in a bag. You and your friend are picking one apple turnwise from the bag. It is given that the first attempt is always by you. The person picking the last apple will be the winner.
If you will win: print "You" (without quotes)
If your friend will win: print "Friend" (without quotes)

#### Examples

##### Example 1

- **Input:**
```text
n = 9
```
- **Output:**
```text
You
```

##### Example 2

- **Input:**
```text
n = 4
```
- **Output:**
```text
Friend
```

#### Constraints

- **1.** `1 ≤ n ≤ 100`

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-13 19:34:54
- **Status:** Correct
- **Marks:** 2

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;

    // code here
    if (n%2==0)
    {cout<<"Friend";}
    else{cout<<"You";}

    return 0;
}
```

*Generated on: 13/11/2026, 19:35:26*