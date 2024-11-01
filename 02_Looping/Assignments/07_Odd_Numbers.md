# Question 7: Print Odd Numbers from 1 to n

### Task Details
Write a program to print all odd numbers from 1 to n using for loops.

### Example

#### Input
- `n = 7`

#### Output
- `1`
- `3`
- `5`
- `7`

### Approach
1. Use a `for` loop to iterate from `1` to `n`.
2. In each iteration, check if the current number is odd by using the condition `i % 2 !== 0`.
3. If the condition is true, print the number.

<details>
  <summary>Solution</summary>

```javascript
function print_series(n) {
    /* Print all odd numbers from 1 to n (including)
       . Note print all the numbers in a separate line*/
    for (var i = 1; i <= n; i += 2) {
        console.log(i);
    }
}
```
</details>