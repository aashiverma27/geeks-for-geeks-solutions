## 01. The FizzBuzz Program

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/the-fizzbuzz-program/1)

### Problem Description

**Task:** Given a number n, print your answer according to the following conditions:If the number is divisible by 3, you print FizzIf the number is divisible by 5, you print BuzzIf the number is divisible by both 3 and 5, you print FizzBuzzIn any other case, you print the number itselfExamples:Input: n = 3

#### Examples

##### Example 1

- **Output:**
```text
7
```
- **Explanation:** 7 is not divisible by 3 or 5.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-16 15:01:51
- **Status:** Correct
- **Marks:** 2

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;

    // code here
    if(n%3==0&&n%5==0){
        cout<<"FizzBuzz";}
        else if(n%5==0){cout<<"Buzz";}
        else if(n%3==0){cout<<"Fizz";}
        else{cout<<n;
        
    }

    return 0;
}
```

*Generated on: 16/11/2026, 15:02:17*