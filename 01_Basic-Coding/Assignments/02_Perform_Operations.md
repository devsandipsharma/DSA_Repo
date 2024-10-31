# Question 2: Perform Operations (a + b - c)

### Task Details
Write a program to perform the operation `a + b - c`, where `a`, `b`, and `c` are provided by the user. Your task is to calculate and display the result of the expression.

### Example

#### Input
- `a = 3`, `b = 4`, `c = 9`

#### Output
- `-2`

#### Input
- `a = 10`, `b = 6`, `c = 4`

#### Output
- `12`

### Approach
1. Accept three numbers, `a`, `b`, and `c`, as inputs.
2. Calculate the result of `a + b - c`.
3. Print the result.

<details>
  <summary>Solution</summary>

```javascript
function calculate(a, b, c) {
    var result = a + b - c;
    console.log(result);
}
```
</details>