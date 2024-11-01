# Question 6: Reverse a Number

### Task Details
Write a program to return the reverse of a given number.

### Example

#### Input
- `n = 123`

#### Output
- `321`

### Approach
1. Initialize an empty string `reverseNum` to store the reversed number.
2. Store the original number in a temporary variable `temp`.
3. Use a `while` loop to iterate through the digits of `n`.
4. In each iteration, calculate the last digit using the modulo operator and concatenate it to `reverseNum`.
5. Remove the last digit from `temp` by performing integer division by `10`.
6. After the loop, return `reverseNum`.

<details>
  <summary>Solution</summary>

```javascript
function reverse(n) {
    /* Function to return the reverse of a number n */
    var reverseNum = "";
    var temp = n;
    while (temp > 0) {
        var remainder = temp % 10;
        reverseNum = reverseNum + remainder;
        temp = Math.floor(temp / 10);
    }
    return reverseNum;
}
```
</details>