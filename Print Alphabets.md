## 01. Print Alphabets

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/print-alphabets--141628/1)

### Problem Description

**Task:** Given two char c1 and c2. you need to print all the alphabet starting from c1 to c2 in a single line.Note: Print all characters with a single space after it and all in a single line. Don't add a new line after printing.

#### Examples

##### Example 1

- **Input:**
```text
c1 = 'a', c2 = 'z'
```
- **Output:**
```text
"a b c d e f g h i j k l m n o p q r s t u v w x y z "
```
- **Explanation:** Printed alphabets from a to z.

##### Example 2

- **Input:**
```text
c1 = "h", c2 = "u"
```
- **Output:**
```text
"h i j k l m n o p q r s t u "
```
- **Explanation:** Printed alphabets from h to u.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (2)

#### Solution 1 (C++)

- **Submitted:** 2026-11-17 19:47:32
- **Status:** Correct
- **Marks:** 0

```cpp
// function should print the alphabets
// from c1 to c2 (space separated)
// No need to print the new line
// The new line will be printed by the
// driver's code.

void alphabets(char c1, char c2) {
    // code here
    for(char a=c1;a<=c2;a++){cout<<a<<" ";}
}
```

#### Solution 2 (C++)

- **Submitted:** 2026-11-17 19:47:25
- **Status:** Correct
- **Marks:** 2

```cpp
// function should print the alphabets
// from c1 to c2 (space separated)
// No need to print the new line
// The new line will be printed by the
// driver's code.

void alphabets(char c1, char c2) {
    // code here
    for(char a=c1;a<=c2;a++){cout<<a<<" ";}
}
```

*Generated on: 17/11/2026, 19:47:58*