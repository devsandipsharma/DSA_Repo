# Question 4: Print Digits of a Number

### Task Details
Write a program to print the digits of a given number `N`.

### Example

#### Input
- `N = 153`

#### Output
- `3`
- `5`
- `1`

### Approach
1. Use a `while` loop that continues as long as `n` is greater than `0`.
2. In each iteration, calculate the last digit of `n` using the modulo operator (`n % 10`).
3. Print the extracted digit.
4. Remove the last digit from `n` by performing integer division by `10`.

<details>
  <summary>Solution</summary>

```javascript
function print_digits(n) {
    /* Function to print the digits of the number n 
       Note: Print all the digits in a new line */

    while (n > 0) {
        var digit = n % 10;
        n = Math.floor(n / 10);
        console.log(digit);
    }
}
```
</details>