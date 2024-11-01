# Question 3: Print Numbers Using While Loop Except Divisible By 5

### Task Details
Write a program using a `while` loop and the `continue` statement to print all numbers from `1` to `n`, excluding those that are divisible by `5`.

### Example

#### Input
- `n = 7`

#### Output
- `1`
- `2`
- `3`
- `4`
- `6`
- `7`

### Approach
1. Initialize a variable `num` to `0`.
2. Use a `while` loop that continues until `num` is less than `n`.
3. Inside the loop, increment `num` by `1`.
4. If `num` is divisible by `5`, use the `continue` statement to skip the current iteration.
5. If `num` is not divisible by `5`, print `num`.

<details>
  <summary>Solution</summary>

```javascript
function print_output(n) {
    /* Print all numbers from 1 to n except the ones divisible by 5 
       using the continue statement */
    var num = 0;
    while (num < n) {
        num = num + 1;
        if (num % 5 === 0) {
            continue;
        }
        console.log(num);
    }
}
```
</details>