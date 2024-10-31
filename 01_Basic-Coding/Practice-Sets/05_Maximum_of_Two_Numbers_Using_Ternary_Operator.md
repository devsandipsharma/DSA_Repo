# Question 5: Maximum of Two Numbers Using Ternary Operator

### Task Details
Your task is to write a program that determines the maximum of two given numbers using the ternary operator.

### Example

#### Input
- `a = 3`
- `b = 5`

#### Output
- `5`

### Approach
1. Accept two numbers as input.
2. Use the ternary operator to compare the numbers and determine the maximum.
3. Print the maximum number.

<details>
  <summary>Solution</summary>

```javascript
function max(a, b) {
    // Use the ternary operator to find the maximum of two numbers
    var maximum = (a > b) ? a : b;
    console.log(maximum);
}
```
</details>