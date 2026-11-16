## 01. Learning to be Precise

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/learning-to-be-precise/1)

### Problem Description

**Task:** There are times when your answer is a floating point that contains undesired amount of digits after decimal.
Here, we'll learn how to get a precise answer out of a floating number. You are given two floating numbers a and b.
You need to print the value of a/b rounded to exactly 3 decimal places.
You may use library precision methods.
You need to print the result (return type is void) without any spaces around it.

#### Examples

##### Example 1

- **Input:**
```text
a = 5.43, b = 2.653
```
- **Output:**
```text
2.047
```
- **Explanation:** The exact result of a / b is approximately 2.04674. When rounded to 3 decimal places, it becomes 2.047.

##### Example 2

- **Input:**
```text
a = 10.0, b = 3.0
```
- **Output:**
```text
3.333
```
- **Explanation:** 10 / 3 = 3.33333... → Rounded to 3 decimal places = 3.333

#### Constraints

- **1.** `1 ≤ a, b ≤ 100`

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-11-16 15:23:03
- **Status:** Correct
- **Marks:** 2

```cpp
class Solution {
  public:
    void precise(float a, float b) {
        // code here
        float c=a/b;
        cout<<fixed<<setprecision(3)<<c<<endl;
    }
};
```

*Generated on: 16/11/2026, 15:23:29*