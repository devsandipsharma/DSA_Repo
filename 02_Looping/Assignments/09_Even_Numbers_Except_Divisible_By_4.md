# Question 9: Print Even Numbers Except Divisible by 4

### Task Details
Write a program to print even numbers from 1 to n, except for numbers that are divisible by 4. Use the `continue` statement to skip printing these numbers.

### Example

#### Input
- `n = 10`

#### Output
- `2`
- `6`
- `10`

### Approach
1. Use a `for` loop to iterate from `2` to `n` in steps of `2` (to get even numbers).
2. Inside the loop, check if the current number is divisible by `4`.
3. If it is, use the `continue` statement to skip the current iteration.
4. Print the number if it is not divisible by `4`.

<details>
  <summary>Solution</summary>

```javascript
function print_output(n) {
    /* Print all even numbers from 1 to n except the ones divisible by 4
       Use the continue statement to leverage this */
    for (var i = 2; i <= n; i += 2) {
        if (i % 4 === 0) {
            continue;
        }
        console.log(i);
    }
}
```
</details>