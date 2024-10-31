# Question 3: Perform Operation (a + b) * c

### Task Details
Write a program to perform the operation \((a + b) \times c\), where `a`, `b`, and `c` are provided by the user. Your task is to calculate and display the result of the expression.

### Example

#### Input
- `a = 3`, `b = 4`, `c = 9`

#### Output
- `63`

#### Input
- `a = 10`, `b = 6`, `c = 4`

#### Output
- `64`

### Approach
1. Accept three numbers, `a`, `b`, and `c`, as inputs.
2. Calculate the result of \((a + b) \times c\).
3. Print the result.

<details>
  <summary>Solution</summary>

```javascript
function calculate(a, b, c) {
    var result = (a + b) * c;
    console.log(result);
}
```
</details>