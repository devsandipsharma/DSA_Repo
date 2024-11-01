# Question 10: Print Numbers Until M

### Task Details
Write a program to print all the numbers from `1` to `n`. If `m` is present in the sequence, stop printing any other numbers and break out of the loop.

### Example

#### Input
- `n = 10`
- `m = 4`

#### Output
- `1`
- `2`
- `3`

### Approach
1. Use a `for` loop to iterate from `1` to `n`.
2. Inside the loop, check if the current number is equal to `m`.
3. If it is, use the `break` statement to exit the loop.
4. Print the current number if it is not equal to `m`.

<details>
  <summary>Solution</summary>

```javascript
function print_series(n, m) {
    /* Print the following series from 1 to n, 
       if m is present, stop printing the series 
       Note: Print all the numbers in a separate line */
       
    for (var i = 1; i <= n; i++) {
        if (i === m) {
            break;
        }
        console.log(i);
    }
}
```
</details>